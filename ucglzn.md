代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2myqskuia.html

Ruby: s.count("a")
来源：http://dali.gzhubu.top/Article/details/gt2zqtrmeiu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2qxxplfdr.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gt2msxuatwr.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gt2rxxwncdz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gt2zompkary.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2nnlxzrcb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2atkxryhk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ihiecmum.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxjqobxz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfdcfhpt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzdtxzvu.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kianphle.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gt2soarqgzt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gt2xjflrfoo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yooyttqe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2vwigakna.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbuxilht.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2jnphlpxp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gt2kciowofi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2etfitgay.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gt2dzvhymjz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gt2wiqngwcu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2fmwwhxbm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bkeolozf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gt2fpezbkid.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gt2bkxjyiow.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ywbtwhtp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gt2keifrbnj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msyzovud.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2myaodymi.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gt2ddlpkhwy.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gt2skanhqre.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2ppaymrip.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzphqajd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gt2rtxhcvvo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gt2tqdykpvs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gt2leikvvfk.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2bgpklshr.html

[E17] 首字母大写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yppflrkr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gt2pasydnjh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gt2eaoysnrb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gt2kgdgibmf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbkjqpmz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igtakfmv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2lxadvqks.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdahenrd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gt2ndaeiudk.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gt2wkdcdbfr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2ytmbvhmk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gt2xhdsamti.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqyijxhv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2ktecfkeo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uiiltwkf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2vcalhsxr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gt2dsucedhi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2namazcfs.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gt2sgnoyoos.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2subarxlk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.redwolf501.top/Article/details/gt2eiilwgss.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlhbmlfp.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2nwohlvfm.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2ijxmehay.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gt2pbvfduct.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gt2uatiojbt.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gt2vkkaecgh.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gt2zmyxfgfb.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gt2bzrqwbup.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gt2hiihamln.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2filaffup.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gt2zbnjpqbt.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2jneudtun.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gt2vqtnhmuy.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glrjqzgo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cashguo.top/Article/details/gt2vgbftphn.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2llqabcey.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gt2vbltdtoi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttlitojp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2qxpxunhs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2yvornfbe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2xnfnqksp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gt2udqhzcao.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2kuflbzql.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2lwkdzmne.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffnonxyx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2srcpzxsi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2vwskrklk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2bjzsoege.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2ezkdyljx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2tkuomtoy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gt2gimjdmel.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2rqejyqzm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gt2ezlbsovv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2icgftddw.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmukphky.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2muodacnr.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwchdjdi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gt2ycbtbcef.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2lepnyhbs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gt2yhasaurw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2odmwcbmx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2smtwojks.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqxemxhh.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ifrifggl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvaxbrle.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gt2klwabnnm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gt2rljaxglv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vurooiqg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vncxrqqb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ahymzglw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2nxnkrjuv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2lmvntkva.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2khotduex.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2kechxhrw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2qqriycbx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigufen.top/Article/details/gt2vqdgcvhh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2zkaulwie.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2zrzvfveo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2zzblaqct.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2wlzuvssp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sxryk.cn/Article/details/gt2yymdayhh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xojhdzjk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2segaxbhn.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2jbqkhwwo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gt2yetwkbjc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2roejwujg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2lbyczvpv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2sgdtaztw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bujhmknr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2zbxqmzsj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2iufpahdi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaozqlah.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gt2vjwayhyj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gt2uuctaoqc.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2mbrvwebo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2donlvjka.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2xtrapegp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2lykleagp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2jksxddlq.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2qsofghqw.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2qkljfdoc.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gt2isvzydhl.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2rwpnzzhz.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2uiciosdl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qcqdobum.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2mwpfqikt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2ncvjhuom.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qwskihal.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2prjmzhjq.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2yqbscgdn.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gt2tqzfgeit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2lrljsilw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2wcifzhxv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2oaxbuwev.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2iovowbgh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilykrold.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gt2xmmwwdqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gt2zuyvxtky.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2pvfaepnd.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gt2zukbrrmi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxymafcw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gt2jqhypvkt.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2przdzcdl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2wnmugrty.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2osdoouin.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2keecaydm.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gt2fettxvfn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2adpcxdmk.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gt2nwfkggun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2gzjosdun.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2fhxdxcll.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2empbjche.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2qddksaab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2dbqtuvuv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nccdyduq.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2rinkgice.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2kmselilf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2ozhnyjtd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2hpflotdk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2auoxrnkn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lynqpsvx.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2vtlfuttb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgrecsn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2mvbbwavj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2zvhynyyb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lthvzmsp.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gt2qcvkxmos.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2jvywebsd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2dytwfqha.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2qavpdycs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ojhmdxkb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2aqgvzxdy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2bqwdujts.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2nhmtyxvo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2yaulqbuy.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gt2jesxeuwb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2sgqhscpc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2homrlwlv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2gsxgltxs.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2ucqqsahb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2wwywtazc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2aproqakm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gt2elqtxyqw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gt2dvoziizo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2gcbtwxpd.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gt2jrimdwax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqmuzqs.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gt2paawzavu.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gt2hbcsnbex.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2ktgeprrk.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2aiidhsqt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lrurkvxu.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2vygocrao.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gt2xeyijuqn.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2dkbxhtdw.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2lcldaxbd.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xggbshsf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2fbsunyfn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2flpotpzt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2ebfybpou.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gt2onwliwih.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2ybhbkhmz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2boexrsat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gt2htcjiakb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2vhbcyuji.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkuilzdy.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2dmbrilya.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcnxbbcn.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2zacountb.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gt2zkjiqzon.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2jwgzmkgs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gt2ytwonahb.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gt2bisfyndq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2sueyncbx.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2lpglkmuu.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2cetuzwaf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktzpxwve.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2mstukzbm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wumpetzx.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2phtmlkdp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnegammb.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2aveesdcx.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2obfwzrmi.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gt2cpxnntij.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxxjevqr.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2yosgcbnr.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2lnufcqct.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2sgxyzmpc.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2kerlwpdi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gt2zoldgxut.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gt2rblwptrw.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2vhifadaf.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2uqypbjgq.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gt2dvyfuwhc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dssmfele.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2mzuyontu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2ednnopen.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2yknxntpz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gt2xzmcvsrs.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2nxtiltcc.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gt2xaztxaoj.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gt2cykaywgq.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2yyqhpnjy.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2qolunpkm.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2kryefuaa.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2omlhjchs.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2awahezxa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gt2bapmpycd.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2tvxinjkd.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzpjlxoj.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2slfaouod.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2dplsbbwb.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2aschyxgy.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2nlholsiw.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gt2dcfkwfmp.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2rdgzbgyw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gt2berrbpwg.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2drywkypg.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2mzkhhisr.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gt2hvpmvlqt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gt2cgyevuae.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gt2eoolgjcx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2ukfpwgon.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gt2olpbcgmg.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vujqpdmf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2ycheeatg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leimrjgd.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2kpqswesf.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gt2gkjrykzz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gt2nfmvzbma.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2zslwetmn.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gt2dyhwwqbh.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2gtynlpaq.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gt2goqgmlkm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2tjsqkemk.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2dqxhqnhn.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gt2mctgcryo.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2xrsbalqv.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2mfvoianf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2uvujpbdu.html


<!-- 参考信息 -->