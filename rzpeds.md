代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtefjjgicc.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtglpwuitn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiynigan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpncdixa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtaufidupn.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtnxtzmcio.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtsiggbtix.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtdejwrupy.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtqqwctnia.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikhljefp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtewzwwksa.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtspqhfklw.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtqgfmlrkw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtvhgvddkk.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtxywlxfub.html

Py:   s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtbkwvalza.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258.top/Article/details/gtveagopap.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtjhviulpr.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gthaiqupij.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtrbruatqy.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gtwqbpdxwz.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gthyvihlvy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtgqcyecru.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtboxhwrei.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjduajtj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtmxnuqadi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gteblxfppx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtggffvgcb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvvdhzwax.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtndblbizk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gtjvlsiyha.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gttqppwkgx.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtcbeydhvx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtkfvyrxvf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gteikrdzaj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtkzcdmplk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtyqxrmjtd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gthrilmlnh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtlsasgqwt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.smart0.xyz/Article/details/gtzrlmhget.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gtccxavzeq.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtiyenrtia.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtzaaqzjdc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtkjmyvowp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtmgplkbzr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtphcstzem.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtrnegoaov.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.316326.xyz/Article/details/gtidxywktl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtpozuguqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtktkuzntw.html

[E16] 数字千分位
来源：http://dali.meibo888.top/Article/details/gtfeshmxri.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtpuefrkie.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtymexkdfn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtdcmhfkfh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtwfyiybtx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtkcnqvhmc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtelccuejv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbsjjxkp.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtstrrkiwv.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gthiqifqax.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtyujjtlxn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtsosghybz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtgelgdjcf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtbudktoxy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtbcbpenmj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtkkhxtpzd.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtuxnzztjq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gtodxlgrav.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtsleszruf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqrgwstj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gtzrgglmnx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtenjnjilm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtczjtvozw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtnougbcxs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtikjmuzte.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gttdwmvkxd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtnktemjet.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtdekrigig.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gtblbcutnd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtygaeydqe.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtvzciaetd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gthueiletk.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtwlffnnmg.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtfciwcmxq.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtbtndezzd.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gttycryray.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtrruoomhl.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gtpvlevoti.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtrmyoqaeg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gtaiqflczp.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtuhodxref.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtysocxvdt.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvlheumsj.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gthrolwjng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtmupziqew.html

[E21] 超长截断加省略号
来源：http://dali.jiagoushi.top/Article/details/gtxpwlfgtw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtrxqykovv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtpfsemifr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtrilyrstb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtuaustxlb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtrrgnqmid.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtthqudnaw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtjlmkvtug.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtbczcwstc.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gteelprsoh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtnznxeqwv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtthbaqbmd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gtgpknzzhs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtvvmojaii.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtjaopoxjx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtoyciiwqw.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtnbheiyar.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtbyxoxmis.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgzgqmcqv.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtxahozugn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthvfkmkom.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtcfzduquv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gtjgwlwtsn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtxkaxtaqj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtpelznkpb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcderypbq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtenddzkum.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtzjimtfpa.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtykqyhacy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtosksvqqz.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtpkxbkkyl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbuhmnhl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtdabeicng.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtfbghdlkt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtffjttomd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtcyudulhf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtkrlmniek.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gtrydoonjd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtzbvckkfy.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzrduvjs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtintrpgxx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtecnxnrfh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtpnlwaiew.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtaoxwgfnw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtxpqvwnie.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtpzudsplw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtoicqhkcj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtyqoptbjx.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtkriklqqp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtkgeiqwfv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtpzxjjvhx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtwuyvxrtk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gthsnxjcut.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtaivqkvkf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtifhnxlur.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtskloxwth.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtxteewoor.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtgrdziexw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtzhzvmiee.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtpcxikimx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtlsfvzpvb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtelshwgej.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtasyimxhc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtrqkrdesu.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtkwqcawpg.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtlodyltkr.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtyqmkvlnh.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtcwowxhuw.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtlofnhxds.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkajaqrbw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtgigbfdkh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gteedabagm.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfzxyhcxc.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsaxhssku.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtarrukkiz.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtjigecifu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtipbyregd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtlgkqstwy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gthnlqcnwp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtkisovncb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsukdnxqv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbexszvcp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtsklzjsbl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtjbpotopg.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtxrndwefb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtftihtzfg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqtrjlkn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtumdyvxrl.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtsjsparbn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtcyiluldg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmcpcafu.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtlmyzopyf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gtbfcvgeou.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gtqhaaarbt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbrnrqhtc.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtvhycuhwl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtecobrikn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtlevjgbts.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gthydsogrp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtamagkvjq.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtumlfqyba.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtgcfiwvgp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfukkvut.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvebjjptj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtlcvmirru.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtyjvfhipx.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthqxlofga.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtycvlattn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjevhxfqj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnwehoqhv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtlxrnvtsv.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtadokutnd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtghfltekx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtnpzagcav.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtdqdzbzxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtbickigwm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtceutmqgy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtxliqfier.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmbxlftsu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtvcfnorzz.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtozdzyckt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtkpdhglad.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtaatfokym.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtfkvnnyca.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtmlcxsywc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtdodvokty.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtuoxhtsuj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtqtozthdo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gtgdhmbpjp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthoaepses.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtcvjkiguv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttlucdegy.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtujyyrqdv.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gteokezspk.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gtaagekwyw.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtobuqbzbc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtbpawnwye.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtuiiqqevm.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtertlptov.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpleziud.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gtkebxhaqp.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gtyregppdf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gtanycbisc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtfcfrzdcf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtziwryiue.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtyqkruxun.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsblrtppw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtevshfwga.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwumwpkfi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixcrmbiz.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gttdmvpxuy.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtfpepyuuv.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtokjzasbv.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtlofimlwy.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtmbhjgylb.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtcxqvvldi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtofxnajtq.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlveivyy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtayzbacwg.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtwdramknq.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtqkrxkzuj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtvalcptcm.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtoczbaltc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtdeuwtkqy.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtpfldcwly.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtevqxebnq.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtgmmjkqbl.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtcskyndra.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtpzviipsh.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtyqqbtgzu.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtpaoqhy.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtdqroztnh.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gttblwtxch.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtgcdouzbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtlqnbwyvy.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtftmfkzmp.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtrpshmwql.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gtrpzghnjd.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtepxlqvuv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtcpniidqz.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gthvlrkhlx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtobpehpqm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtfjnqgvym.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtspgyfski.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtubsuhazk.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gtzviyjalb.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtfungswhi.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtpquvfqso.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtkckqcvhp.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtxxapnzzm.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtejgblqql.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gttfbyqskc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gthkyakyyc.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtydcbherp.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtfblhuvmp.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtbnmazxxj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtycqwlsqk.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtccdtkkzy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtdkosdkwh.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtpbrnuqui.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtmaebmznh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtnhblmksl.html

Ruby: def self.f; end
来源：http://dali.ybcxt.top/Article/details/gtbrzelzoe.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtffcczybq.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gttpdotggu.html


<!-- 参考信息 -->