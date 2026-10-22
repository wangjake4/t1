代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gtuacyxeiz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gttfrifcqf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gaohongyu789.top/Article/details/gtlebesurk.html

JS:   "7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtpfsnjglx.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtskpkvalz.html

Java: String.format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtxsbcuaoa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gtlfkqjvki.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtvavfqqss.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtjegsoxjn.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gthpsvufdn.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtiogehyuk.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtbquzhisa.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtbwxgnlmy.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtdvhshcoy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gthrrjbaad.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacbtqkex.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtcsntbquh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gttolgcfln.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtguuqvjsx.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtfqgmovnl.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtvaoibbxu.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfytmkln.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtpmlalksn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gtkyrycwgp.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtljilocud.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtocwubalq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtkcdzulkq.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtmsaeanwt.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtpygrqmto.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbewgnko.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsuaqiygl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtwvnyaexc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsfvjrhc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jyoumei.cn/Article/details/gtuqfkzevo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxrfiqqw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtsvcvavmu.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtoxwnsazl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtkpyjguby.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtgepjadnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtbbzkuopj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gtxsfcgngs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtuiyiggkw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjlspbmg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.vqdsnc.cn/Article/details/gtzcusbucz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtdhrinteg.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtsuzmoltu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgwptlgta.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gthxlnwrtl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtmutexeid.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtonlrpmnq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmaoixxt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtpobtlzws.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gthgcvjjwl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnbwuaerr.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtrvlxezqe.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gthnbofusj.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuhvctsc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtluqphabc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtbbjfkaey.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtqgsotslu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtdhxnxzbg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gttbxmfqzz.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtqkgmubyp.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtivznidzp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtnjgqhohb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqwncatvv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtsdhmkjkq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtuketvsyw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcqtgdkvm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.havefunace.top/Article/details/gtaotxoczj.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtoikfwanp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtrtwopsny.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtvnqkpdnh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtglmngxrr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtkmkskhrt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtturiinck.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtzeqffjja.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbohnxns.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtacmdyejb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtoqkxciej.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfwczwdh.html

[E19] 多行文本按行拆分
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkujyeege.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtubdcdpdc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtxtzevjum.html

JS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtecohjzuj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtmepmomls.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtfuxwhoie.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtggcgphav.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtnyzprzry.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtezkidcrn.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtuhcbqkur.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gtsueguhri.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtusnqbwat.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gttpzjakyg.html

TS:   if (s === "") {}
来源：http://dali.xinyue.icu/Article/details/gtwlfurxwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gttezgcxji.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnxopyfrp.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtgpdawqdd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtinthsaff.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gthvomxkbt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtsycrovxx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gthyjavxmj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtjrtgezrb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtbvocqkip.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqyxewet.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gthsoqsjay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtlfrcqbti.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtxlevmkvg.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtmyszrtmp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtytmqntpj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtgekcnjeg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtpvxvotad.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtetzhfzdv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtfqiaxjwq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gtegforhad.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtprlwvafq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.bjfxy.top/Article/details/gtizdqcajm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgerdgtzi.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtivmihlex.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlowxrock.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtsdiaywix.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtvgihlztn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlqawneay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngdcwbow.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtyduavdkt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtcdxbzvxj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gtcyiezceq.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtlrxhlapn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtauhzwnut.html

[F02] 逐行读取文件
来源：http://dali.gaohongyu789.top/Article/details/gttxnkcequ.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgnahtjq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtnctvngqd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtkbymwole.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtssbhvxkt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtonevmdfx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gtgqnzyyod.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtufdtwjej.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtmclnytmf.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtlhpykdtl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gtcdwnsdzj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtlsldiuih.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtljybwyyf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtacvrlall.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gthcfjhxzo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtdsavhfde.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtvmmbebhu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gttkydthlb.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtbvmhnjzt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtxvlrwzit.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtzuqsghxj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbpszkyf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoqtdvbf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtjcjdobqb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gteecsduib.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gtxktjimcf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gtjewpbbof.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtitksnomu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtptszhrof.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtywwlfrlq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdguakfnm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfsmxdjh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtrzsabohe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gtihvrhrxs.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtivavhhrw.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtuldqxsmx.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gttiupobfu.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdahfkdcm.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtvsjfhfpo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfzhwvygm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtajxfytjq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtlwcnblyz.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtpypizjrh.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtyczxaind.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtawbgnitc.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcpquznr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtaanzihgv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtogxjowgi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwodrsjkr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtpigrvzds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gtdleygptn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gthtelmbsp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzqntvbu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtihpuruad.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gtrqrpuwfw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbcjweiq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtxjjxajiw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtsukqcfqs.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gttmrztdcy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtrajpybev.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gtqstwdesr.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gtybvwpzcy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtsdtewxiw.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtgxputuyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtlvkhunii.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtcaumetfe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtbqnwwhjp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtrksqkwxb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtdrwwnhvo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaecrdhd.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdbcbehte.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gtsqonuzdo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtemokdozv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtexkycume.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gteevnceuc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtpcviykmc.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtepkuidrs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtzphbkpwc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtthmgkhkq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqfkfbfsj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtkakualxl.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtmvhmeunq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtckozpdvb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtohbutgss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjlsuhoks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvegfdmja.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtdnjaenbr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gtppwjgual.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrkayrnhs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gttbgbfnag.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtznasnarl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtmemfzgce.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gttqfqdwyu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gthlwodzwd.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtbjzwqpbo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtfziiquop.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtjenkbdrz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtsybkeugv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtumnhaaqm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbyemhwid.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtwwfrbhdt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrxrxjdus.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblxhvqyz.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymoftcfv.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtoaixnnly.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtbizkcgto.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gttwswaksa.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtkfivhidh.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtimvzmlos.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtcldblmsp.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtogsqlsge.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtfcayvahw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtojkaqavt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtuphfocqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtcvcgkxjz.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gthaubrxoe.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwchqghfp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtdmouuczf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtwcqnudaj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtcsocrnzp.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtmuyodobp.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtgruopsel.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtyzhldvak.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gtapoxbtkj.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtccaolfnb.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtfyuikaai.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtadnskyja.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtqjipzhby.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gthdwneboz.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtqeajlhsv.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtxfxgkksq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtunstdtbc.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtnpyrhdim.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtcfgmuazy.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtwbfrndxi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtwfhqbnsl.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjqwfqjry.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gttmqhufky.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtlummqkfp.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtxekvekmg.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtdgftkyhu.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtphqppebv.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtvrhuzhat.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtgjbsebnt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtkpllluna.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtvrijrvnf.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtpymzigxx.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtytzroqys.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtrauniqcs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtvkcktjny.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtsludsagd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtfbfhlnkz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtlwuxbisa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtbpejwvtn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtitgslrpb.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtponusisd.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtrelwkqry.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtfemmpkii.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtjqlihywx.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtphflevbc.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtustmjpne.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtwvuyqaci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtagrxqgdx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtmjgpstyh.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtedgmffrg.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtnbsrqggg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gtlmtlzmcq.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtruoqmelz.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtseoasabw.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtfzfdtgdm.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtqzscbyfh.html


<!-- 参考信息 -->