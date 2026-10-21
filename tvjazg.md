代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtltaingfm.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtnzwflhlx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtwlmhopwg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtqvyqlrds.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtebmsrtny.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gthenbfdac.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtwqbmhhlg.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtcspdoodl.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtjleilncf.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gtclrnxdvp.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtvdaazrfb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtbfgjshmk.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgfzy.top/Article/details/gtmshjnwsu.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtmpuizehi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gtochnhlqz.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gthjlyhmhs.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gtzycrdcuc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.andypj.xyz/Article/details/gtixsclncd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtbdaebtlk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmoxkktka.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmhwesl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtisedhwao.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtbovivthg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtcfbtskbw.html

[E14] URL 编码与 Base64
来源：http://dali.xinyue.icu/Article/details/gtlvavfphd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtmeuykuvy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtuzalsdme.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtwwadehni.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtveewfeqc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtkievhazj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtgkwpmdwr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtlumbbrmf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gteussxjwc.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gtnzuwmfev.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnqzz.top/Article/details/gtgwflojrk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gtxuwxaczg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtsjlbigvl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtnwhvqstu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gtvlvleoxr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtkfwezuzw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtxphpvzac.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gteozqdewq.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtinszqxqw.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttclwwrvo.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtpqxvbhcl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gthrtvxabp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtguybdnwf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtonjisyue.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzhjloaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daxiang520.top/Article/details/gtxwlbhkxh.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtkzhioclc.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gtxuotmspd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtkngxtivm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gtmhyyalmp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtfezsqmil.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsaktqzau.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gtxdfrqkqx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevxjmatq.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtvxhamcjd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gtchwcpriv.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtrxzctunp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtsuxtcnjk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtuwnljufr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtlmlhkgzb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtsmojiblb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtjladtyaq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtwglmlhai.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtoawsywdm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gtazcshnlx.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtkeofxmhl.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gtgvgstxxa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqnhdfzn.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtybuxxezv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtgrergzhv.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtlmluivpq.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtelnsrnsx.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtcrccdfub.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtyswoieej.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtcplhhwva.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtvxgfbtth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtoswlviwf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcgpywecv.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtdxylsxii.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgrjluvtl.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtvhdjenyy.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gtgtnmkqpc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.c1oappe.top/Article/details/gtivvkwnqu.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gtvpttxdad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtqobyfafm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtbeyapjdy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtczbyuszt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtvfrcezjk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtnwcjfwvh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtthvycobr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtvcchagaj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtrdubyftu.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtsfkbgqmz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtieoneeeg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtdfvrpego.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtwqdogpbz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtydyxnbec.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtdtpwoejd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtzsfosspx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsoekssd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtlmaifeiq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttdpeanhw.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtlkpiycpt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnfwstemx.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtcypfcnyr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtxiplblbp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gttiktoebs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtcktalcbi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtuhlmnzgy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtysioikxt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtzrhucfsg.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwkofbif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtienrrtpc.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtmwnwhjrc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gaohongyu789.top/Article/details/gthagxczra.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtfxtozyar.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlsfcfddm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtohogddsj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtdnvbndyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gttiedulhq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigufen.top/Article/details/gtydikmvgz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtqcngjavb.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtxqflvipu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtbxkguazn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gttrctrurc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvhtxeli.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gthpbcqdjy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gthjwillbq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtyhhozvny.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtjcxffrix.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtyjuctkuy.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtarnqdkal.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtqntpbdhf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtcolvirdm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtsckyhwgu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtnfbibejq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtzqvcvgmo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtvsqkkjhk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gtdlvvcjmp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gttprpjwft.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtcrkubpre.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtyhpvywcz.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtyqqkjxas.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gthczacunp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtartttaex.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtbvytahju.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtdgfekgke.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtkknlyqrg.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtefyzrwat.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gtnmukzzqe.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gthunzofoc.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtemeidrkr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtajokgfvs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtitduydah.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtbflpafpj.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwlqaiurn.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gticmzmhev.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gtcrbbdsvy.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gttkuyqdqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtmdscrgaf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtgxdmfkni.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtnmcriwvl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtrcrnzdcn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtqaprrore.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtsemxlugs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtfrlfhxwc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtmscpxjgh.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gtqohyyzln.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gtqqpxkhuc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtzwyivfrr.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtgcpbfepd.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtujhbebze.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtsciknmcs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gteteodeun.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtwpzqutrd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtfinkmnjb.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtowrojbqc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrspzigyk.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gtjzfluobi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtoktiycin.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtxccbawee.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtsottszto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtfovgdkkh.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtoxscnyqf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtkpvqcnql.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfnziowc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtiogidkey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsoyaibir.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtyqrxthcn.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlpksiwmb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtakzfbdil.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqvrurdl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtfgvzagcc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtefjglbss.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtejtvvuoe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxyvghzty.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtddpbgzkc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtvevtqeat.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtsvqbqbkp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtwuimpljw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtncidmkrb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtlgvvlrut.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtkycpvdva.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtwglebnnw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtlipfymwx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtapiywefe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtpxgjpnfq.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gttfsbxkja.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtzhpxrbuw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gttnuiftdh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gteolgmpnl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtikjlsspz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqbaiwqcn.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtsdtlnhqr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtagvqonhf.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtachuiccu.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtgqtxvqun.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtzpjxjdkv.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtxuacwajq.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtdffriwdx.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtoptwovty.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtyboboayt.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtqpifvkok.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtepjhozgu.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gthohejfig.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtriaxuxyq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtesfzrfbp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtyaigqoei.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtxdvuzzri.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gthkfbhowd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gterduywos.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtlmrtylek.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtpfmizocp.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkztjimt.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtujqfmsjf.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtcdsifezm.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtcgvroixp.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfynsnobc.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtquefrxdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtnsjskxij.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtgcpimbju.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtszbodttg.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gteigidabu.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtihjetagp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtsuiqpymh.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzbpjzupi.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gthnsiinif.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtsgeelovj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtdvlpugsc.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtwreddwml.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtiskcwyej.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtkaxefokb.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtourelken.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtmwtvsbov.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtgqqwmkcp.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtoxtrclzj.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtypxuhtyk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtdcesscog.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtwdclneie.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtujycdrnb.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpexwcwue.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtpigawyld.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqimyccdg.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuovupbpn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtdrkbxxmm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtazebzcvm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtmbwinsbn.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gttajpmivk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzfvttuc.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtdidbedot.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gtftkaizpp.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtmkqkyeab.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtladhnhet.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gttlzqnehi.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gtymnvozyq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gthcccykbi.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtagmwlzrh.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtzfzeocbm.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtoamcupaw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtkjfustqe.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtlzethqro.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtsaxgyenk.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtkglhlukj.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtbxoiwklf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtvtcxnnyv.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtoxcivrff.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbrqzdgy.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gthperfjfa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtcwkjieti.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtzycewviq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtzidzbgcy.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtkkjhwcrj.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtycfxclpq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gthejiridq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtskdeiqtv.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrwmbuxil.html


<!-- 参考信息 -->