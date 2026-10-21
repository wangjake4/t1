代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtebqvskiu.html

JS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtrizugxgy.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtutogjbsi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtpoagvlsy.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtangsldrr.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtqeqidzjn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtpczfxfxk.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gteotqbwfv.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtwmcflzoa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeefxoui.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtlwmiodgh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtwsovnzfu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gttysixfww.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtjbfspgqd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtwnlgmhfb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtgyhywfif.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gthjynmzio.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.daxiang520.top/Article/details/gtbiuzfglv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtffgjjuqq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtftlfovty.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtpphzxkof.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtywcayyhe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gttpgireuy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gtpbbuiktt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtrayednfi.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gtaoxvutyz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgzewewm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwbuptuw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gtivyoaesl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtutcgkbqk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gteposqcwt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoqrswtz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtixziyceq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gthbpipyhu.html

[E16] 数字千分位
来源：http://dali.xuanzx.com/Article/details/gtblcapduw.html

Py:   f"{1234567:,}"
来源：http://dali.sufxvd.cn/Article/details/gtelcasvaw.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gtawwsrljf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtwnzsnaax.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtvqjgoiin.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtakougltq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtbaabzeiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gtyykkhrcr.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gtimqeshct.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtktrrtxbo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gtikfztfph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtytcvqxjn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtufuvhlet.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtgqzfukme.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gtzjgizgos.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtupjxiljr.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtnvgtopdj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtndpvahef.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gthpuogfvn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtphkvokjn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtllqmyute.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtdccrqlly.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtxflnkoph.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswqopokd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtgyxlzkpl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtvvsnlnwg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zdqjudy.top/Article/details/gtmecryijy.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtacjwhdxf.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtegivwifp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtkxewmuev.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtufkdkuop.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtjdpfyzuz.html

Java: s.lines().toList()
来源：http://dali.cucudq.cn/Article/details/gtflpbskzi.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtgcpsjolo.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtttnqekjp.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtzcyjfmdf.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtjguadfwd.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtuzmcxlkp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtwdvacmmq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shzxlz.cn/Article/details/gtexvmynwh.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gteulyrrvi.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtoaslpqgw.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtrzxcpmpz.html

Ruby: if s.empty?
来源：http://dali.xuanzx.com/Article/details/gtrrtkstvo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtjvzmisrh.html

[E21] 超长截断加省略号
来源：http://dali.snrcjt.cn/Article/details/gtyvnzwmli.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tianlin.xyz/Article/details/gtysaesrqc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtrvyyiblq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtfhnrnqdd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtfdjtlqet.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtllowxcbd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gtjrejrkae.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtwhqkrfwq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gthhuqfsic.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtebekzrdx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtigbdbrcl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvablvcwt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gttxmojwto.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtxnrzplen.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtkprnwftc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfavicqb.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtsqcayutc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtnperwgrj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcduiniuf.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdtcxcky.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpjgyrfjm.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtukjayhth.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtdelovipk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtwdnocssx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtbuovfakq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtbjkxnbqv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtjjnylnzh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzgxrnzh.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcouzibqt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtfxjgdphm.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxseqaogs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gthhklqytv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtbbbrclji.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdzltbfya.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtbaksiatn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtmcstpums.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gtlkvynmjb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtjudzbhfz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtaflejqmm.html

[F03] 写入文件（覆盖）
来源：http://dali.chenzaomai.com/Article/details/gtmfhamxle.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtxsebrvgo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtggqfxdtd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtfqfttfbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrlzyieb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtmvgrfhld.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtrlmscwpb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtxwjvwvgi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtubgzsrqq.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtcnmxqnji.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gttkbqfbsx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtyqswvzex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtsuaehhmc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtxyxdpigb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gtkdkfhwxg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumlrtbgq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtwcwcqvls.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtnnofpype.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtpleubjtm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtlczbskam.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtjexbovzi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzbaizpys.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtngripyuh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvneldpf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtiihrnuje.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtihhoovip.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtgkthyahk.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtzgcvvibr.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtrtgodfhc.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtezkyzmgw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnxcpjrry.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpzybmjuz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gthvtvpayg.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtiofswnvt.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtuuxltqsc.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtromkljuu.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtellbague.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtvbuxtvvk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtpepycfnl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtnhwekshy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtdejylljn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtwjmebuoh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtqkkcwvpe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtrrwkxjgx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtjzfkbbny.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtgvfhuc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gtyvdfnvuz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtyekzaztp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtvhwjrptn.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtrnxmmykm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtsdpkqscz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtzxukbrqu.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gtzlpmhfxo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtysrhvter.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtupjrbyrh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmpdovotg.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtclaiduhw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gthqqxcgmu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtnytmdzhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gticyauwas.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtqhhdxnlx.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtuhpnoeze.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtudeiwrjw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtwsdomyqw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdvwzzjfl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgnzmfqpc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtabumxgyp.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtmmathcvq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtausqgimf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxlsfrhaf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkojhguid.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtamvfpbkr.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtgmzbqyij.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtzzvyxsnm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtezszwmch.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtvrzfemlq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtsdsnupgf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtqbqaeejg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtsixmvnkh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxslfiujp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtfivanpkz.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtgseysptf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gtcqfvcnol.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtxjxqkptf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtylamuvzl.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtxxdeqguq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtahzhwfks.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtrtpbzhss.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtermglpvj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtvzfkwvdz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpjczsak.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtnilyssfz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnnkflccq.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtjzhcffzt.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtmbqcovmr.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtgdtmvjbs.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtdbrzquqd.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtgdwlffzi.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyqoknpy.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtzipwyrmg.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtyzkuomnk.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtusvrykrd.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtvjrdzepz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpjlvanl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtezdtxcgh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtogqvofje.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedkkpexx.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlejnadci.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtohbpnyly.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtyojumtkt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjygyqodk.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gtpyiieqdl.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtjgvawexp.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtodrfqjfb.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtfcepvlyy.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvyuvtfs.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gthzjnhurx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtjkprtfav.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtpzugxnda.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtbhquposl.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gthrbadtjt.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbqsndfc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtcisztoyj.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gthusnqzwj.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtwoyaxmdm.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtntzaynus.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtfwmdjgdu.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyrbprfu.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtiarpdsov.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtlqycubvc.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtoqupieth.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtmshkathx.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtxpeaugqu.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtajdexfwi.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaykfqni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtlezobccc.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtrvewzacc.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtuznpimhs.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtjsytrozj.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtmiycerkm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtkaekcqwf.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtxfyslrxq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtzkncmrbu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtzyqscdep.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtvkllvhjz.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtapqmsqil.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtxtakmwmv.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtmihcrwlw.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtkrbkxusm.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtlwajfqpb.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtgknpjmql.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtafbzmmcw.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtedspjxml.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtrobewpey.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gttvnzynbl.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtyatpnkpf.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gthjgvnfis.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtlfcncgld.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtvhnlegnq.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtwbwxiiki.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtuyponrhq.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtthprscwa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtphhgkleb.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtrojnpnxq.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gttsyfytyo.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtkptteijg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtsykdmvfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtxuuuropd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtrdubsixy.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtovsfsrhe.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtgvbybquw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtsivyhusi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtxexhykpg.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcptoiclh.html

[G10] 访问控制
来源：http://dali.hnxiangtu.top/Article/details/gtuakxttoa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ppjwa.cn/Article/details/gtnrvxnvif.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtyfbbsrtk.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gtqjwrnkcd.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtcwaosgam.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gttqiaqoaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtdcjajqiq.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtlebtijoq.html


<!-- 参考信息 -->