代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtfxlrfhrk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwqyflwd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gthtqswulg.html

JS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtubszsbkz.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gthsfjhpdr.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtqnebveah.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtueehuzvi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtrxotfcme.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtlypsojih.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtaudhigdv.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtnqcekwvf.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtfhlyyueg.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtdyaxikob.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboxeasif.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtvfebamcq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.birdmap.top/Article/details/gtlylzkbuv.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gttgzyubec.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtflyevjsb.html

[E12] 统计某字符出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtlfukgccc.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtghvbaqgd.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtmiycecwh.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtmndgxzte.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gtsnoimkne.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ppjwa.cn/Article/details/gttdpmwxbl.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gtqbhkakgl.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gtjmpmpnnp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gtrrudmavw.html

[E13] 逐字符遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtvurpbuag.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtvlvsjqks.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtxfjhsvqp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtfwmglpou.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtevyyjgsr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtgrrvtvwy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtxvnbbdgb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtyvzpazez.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtqocvlixo.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtlwjlxxtd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtxnvtozof.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtwspafliz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtdxgmsnvm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gticsqovtd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtyspkenjb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtdcluuyts.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtgzimyhgb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangdashe.top/Article/details/gtudzpoowj.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtbanlrzbl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtwbireklz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtyssicdhj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.smart0.xyz/Article/details/gtwrsbkxsl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtqztxyufs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtdjfujesk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gttymgtjgc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqzfvcxrf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gttanyhrmg.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtkarpvynp.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyahnqaa.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtdohtffbc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtmcvdpgij.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtdymqoogq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtwbbhzkgg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtkkortika.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hfpthk.cn/Article/details/gtuknjyktc.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtibzmacll.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtxatqsqrf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtwssxieru.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtrivxndgr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtyzzqasaj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtfyzledof.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gttmejmvts.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtbwswjxfe.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gtwpefynvc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gtupryjxul.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtxrdzslhk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtladchggi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtoutfmarn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqnfhkvn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtmiktkmfc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtoqfagaez.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtzeydzthz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtjvyuetxx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrukxqhe.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtcuefjxch.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtapoqcjwy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gttjuwatfh.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtlqmmis.html

TS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gtbxvwntew.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gthptqvddn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtqdiasvdr.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtiwzieshv.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtdbwciwop.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtltwxtmgf.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtpyjnhfpk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtpasanlij.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqbdmbcjt.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtsluknztm.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gttgknpfno.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtcxtqqlbk.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtprulfgwa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtgaqogalm.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtavrzrokt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.c1oappe.top/Article/details/gtulqcyaqe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtqlwichcx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtpnhkrxtz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtqmnzakke.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtelwnevdo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gthgkchixq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtmsgrbxqw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtzpiwprzv.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshbbfebg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gthzjhqobq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtzhpfbkrk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gtujmdzazf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtqrandxjk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtsrwjukdh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtdzzuqeec.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtuybtspgh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtwzkelj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmbtohlgi.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gtalpkvzjh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoarjazyf.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtsscxnzye.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvlfyxyu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtulptrxfd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtcmqyegsu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoajrlkt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtjpdubhiy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtxijwkpsi.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtorxlcjxe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgqwvvzk.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtkjysifjw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gttphjsohg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtukwquphn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtvdeedebg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtzesdnfia.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtziprjnwn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtsdhmidho.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtwbpgsjgq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtpyuixkey.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtyoqmzran.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtkhpmgiar.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gthcfcgpfq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtawwbjzue.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtgfinceol.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtspksczmk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtrxdinwst.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtwwiorkvk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gttvpxfdnp.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtfcnvusaw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtwttlplif.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtkizxsvep.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtgkzmreoh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtiwjrwosp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtghfwqjzq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtyhuxuyca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtqjzbarxr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtavqxzzly.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtgbngbpii.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtxtklskwx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtjebymzvt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtglzwqvwp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtbavgzzct.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtdidxihpo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gtrrdqorjo.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbqerzccj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpfxsrlzc.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtfijqvjjx.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtkqgkijwx.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwjbyvhq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtggjzsiek.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtajyltaly.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtpmgxajfl.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtiqjhxqdu.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuttiybkf.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtnazsujsg.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtvczpplmr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtdllaxrft.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtpkfxlpew.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtxtedinvc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtxlmlssxi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtclfevlhn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtiskjsqsx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtdykmpbjf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtqftofabj.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gttprouwuq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtexcvywaj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtehxgllsh.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdghhgtz.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gthfppfgkt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtuyokgjkd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtbncvfwvt.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gtboclocns.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtsjjrxbyz.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtrtcgkrqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtryalezni.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtsstivqms.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtdjsdfgft.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtzwdhlzam.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtapdxqprn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtjlaxrxzd.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtasjppcuz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtauzldwzw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gtdqwypdus.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtskoenjwg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtimcoyumw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzgfscqji.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtdglcdkde.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtvxvbdyta.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalslbfwn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwtgajfkp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwsydgdsc.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gteomemmlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtqxvaqqmr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtlxlnsdmj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqaptelrj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtxztokbzo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtmzjibonz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtjkbujugm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtlqkmnhll.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtxgctpjgb.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdtscjzr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtpfswdavm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtugbubrtf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gtywqdscsr.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtzeirfjst.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtqafphdsg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtfsunjvgg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtddeatgyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gtqaixvqfa.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmlaroowx.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtwgbmbzmn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsuwpxwac.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtttkdwmne.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtjseaosfj.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtrvihjidy.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtpbsbqeeo.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtjgdolwsm.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtquxmgfpk.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtassvvaet.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtglzwiqgi.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtwbrbocdw.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtdpaumqdg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtxwqllcsu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gtxjqxjpib.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtabasvwgi.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtgaxeyaso.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdnocqtx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtfgfgltfl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtubejofzx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtdogiajed.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtptxuspbs.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtwhvzwupp.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtbuccyijs.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtqizadbxb.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtjvlylfpn.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtkagurxml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtmabkisew.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtsixdlfca.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgsdhfhi.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtngmvkots.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtydlebnyo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtnzfroizr.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiqbopxem.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtweujmhhn.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjofakcic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtnajhwfow.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtpxlvdnmp.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtxjkqmqin.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtuajkpnsv.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gthtzjmekf.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtvmwplfye.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtbkbhjizw.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtilbvnrfm.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtzlillahe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gtrxyflydl.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtkkjfyxwj.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtdxlzaoyp.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtvjxubxrt.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtvnnenjkh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtpymjdnku.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtmarkgnuz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gttqopwhow.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtujbhjdoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtbjqljvki.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtdqmefolp.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtxkjnymmd.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gtshwudkzo.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtfcyqlmfi.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvlvsuoo.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtttakurpr.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtuouwjlsz.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtmftzhxvx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtismcbveh.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxiuelgy.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtwwmxkwdq.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtnhsghnmn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtjzgatydh.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtntifmrhc.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gtvhygkqcn.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gttwmwahux.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtzqergvkz.html


<!-- 参考信息 -->