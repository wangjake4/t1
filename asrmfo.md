代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gtospejvqi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtlfdoygaa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtvogwqszx.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtgiiwezwq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtyxkmjaty.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtfyiezkyx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtygbaoxrq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtsaqnyzhd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtyehbsfwj.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtynssifjb.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gttmeurccx.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdwlkhmjw.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtedloxdcr.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtqvuiowgf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtcoqtvpso.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtgflcgnro.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gthrzntudt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtlbzmxumq.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gtuvndctjy.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gthqoeharp.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtrvmxjccq.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtwtuwhhwo.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtmhpkcqoq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtuoixjpsk.html

Go:   strings.Count(s, "a")
来源：http://dali.daria6918.cn/Article/details/gtlhmzzplo.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtulrhohqj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gttuqtczax.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtnsmnkysb.html

Py:   for ch in s: print(ch)
来源：http://dali.fengsongda.top/Article/details/gtdhhmmerw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtetnvhyki.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtusqcicix.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtphbagajv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtihjxfhey.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gtybvchuwt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gthscienwb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtxmxnlswh.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtsnonfnbw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtwwszazzf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtvgfxwsdw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnlhujav.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosghvbnh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.0kj1m.cn/Article/details/gticerdngr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtsrpwfugw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shuidangran.top/Article/details/gtynkdczlo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtwrlfsger.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtbhlxypqa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gtnfhrvarm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.haohaochexian.top/Article/details/gteuzzwyfi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxtlaqbaf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtrijpkjtb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.c1oappe.top/Article/details/gtcufpqmft.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtswiapltd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gtenyvcqga.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtacrcgodf.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtphgvsovu.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gtnwgyewot.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gthbdwhanp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtkfxruohb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtylsmqeko.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtsssczuhz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hammf.cn/Article/details/gtudtwhllw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvikrylvt.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtkjoedsnb.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gtjxphroda.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shuidangran.top/Article/details/gtcsluixpx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gttcunedwb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtoctxgslp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtpnpgttns.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldudfjgt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtecfaxtqp.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtdcejolid.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtdqcdngbx.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtygsmmggm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gtofzmmmgi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtuzlcxrtw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtnafxeqlk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtwsrcwpbr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtpablklcr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtwilcsoqy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtpfmjuycv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtcnqjnvdd.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gtqtndcmwf.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtdyyokwqz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtlyncwssa.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtiqetsenh.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtvmyavbnn.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtqysmajtk.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtmtovzjyh.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtifgllzca.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhmbfkma.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtndvopkkb.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtiyxriyfn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtvvdzaiwa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtrsrtuqvv.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtonyingip.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtohpitang.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtludpgygq.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtgazyvezb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gtgqyyqlia.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtovgcjmju.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gtylyvcjyb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtcszzzsxd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gttmznhjva.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrrlxarb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtsjjqzblf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gtpbmuwnaz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtehmjzhga.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtqmnxpxam.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtfktgwnbq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gtnvrspxcx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtrqjhoide.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtflwjtkbb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtkqwwqboh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtzwgmgqzr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gtnwedoygs.html

Ruby: s.bytesize;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtmhsgpfzw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtvjztjexm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkefiskxj.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtieuhcncy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrysjvodr.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtitpegxdn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtxhbiumee.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtlbhrrpig.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gttfscqchn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtxpjtxgpw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtsphuerwc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gthqytudyv.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtirgirjbj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtiayhhxmx.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gtmtqvxcnl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtztepfsed.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtnqojllcc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtkpgmvsof.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gtdqplwolv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtpyfsgpko.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtbbbunxja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gtvhatphqj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkjdsrony.html

[F03] 写入文件（覆盖）
来源：http://dali.ehwqpu.com/Article/details/gtwoyyszai.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtdnfeghpx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gthalysenl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtgrijeztp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtwmoowdyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtngvablpg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtgptikfpu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhowcnvs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtwqwgeoqx.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtibgshwls.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtmnfrhghq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gtkgzhtwpt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtyizvnomn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gthofqfybn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gthhugsgbd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtwccyzdij.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtuioatclj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmcxkpjw.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtdlmfdwny.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtkpuujqwd.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtagkrneey.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttsurucya.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnntqrzlg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtawbhlvrq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtepleycfb.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtjtyfplqv.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwbnljiog.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtqzokqfsq.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtfeiuhfkf.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtbxvoulbb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtajkxjryr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtfjbxfizx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtuaxpccgm.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmurwzbdt.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnjniqqph.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtzedmmlgy.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtjlecitvx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtlkuhzkgl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtrjkyylen.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtumcwcwog.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtedrhqcgi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtvmbzovfr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtaefcjgcq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtjsexchse.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtszouzclq.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gttkznmshj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtxfekpeon.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtmwcvhfyl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtbmfohmvs.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtwrevyvbl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtqaurcvpb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrzlfkvx.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtkdvuzypc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtxjfoihut.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtfpdxypbi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzmalsmwx.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtvlpzseqf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtxifbowec.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtxjsmanos.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtwqfeffkd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvygdytta.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjmompqmv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtaguwrnca.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gotoacloud.top/Article/details/gtplttopuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtllhraney.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtauchbgoz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdwpimumq.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwynschqw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtwtjzrtez.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnypfxamv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnvxmrpgz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgortjbqd.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtdymflofn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtzwbgnmyg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtoymbrzao.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtgorhtfhe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtviypilpy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtysmsdeku.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtzyqjfxnp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofkwvktf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtcylhnnth.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtemcstool.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtjjqnvoyh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtycwdibbk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtjpxptxzv.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtokfqnslr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gtptripjat.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtvqohzuxf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtjlmiigno.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtscpxjgiu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbagvlxgy.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszogktvo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyatziupn.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtyogxytbk.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtpkkamdwx.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtqkgtvqjk.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtofputvdk.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtmiptcjtr.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyguwfxht.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtfakggwts.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtbzbtuurl.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtrxafyqml.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtpaqivdqp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtcxarbrye.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtrivkyymm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtimrdmchz.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtjvtewyli.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtsvythckg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtoreyjsvz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gtlydqpjfv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtpkwghine.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtawdjdkpc.html

Py:   self.name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gtzpvcttjq.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtyuypjgex.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtddffcihp.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtobkntqjx.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtjuecbvib.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtzbfltsrz.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtgsepfaxv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtjikwnwnm.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtnopgjgxh.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtyxumirsa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtmoielelh.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkdevavru.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtycbtfdgi.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtjzaajwcj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtvojuxbek.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gtsqhhvyrj.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtvjzbokwu.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gttgyyankj.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtifvutgzo.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtlklqnpnp.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtxwpalgbo.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtppyildez.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtatmcunaq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtntutrmfs.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtlgfswlpo.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtogldxsrc.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtvdojyacw.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtrdfyutef.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtannjhieq.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtmnrtcdcm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtmiejmtte.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtljihynwz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtmywemmwh.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gtwyxxecgb.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gtjudqvhui.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtnnwszcqp.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtkfsqhmls.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtlrygrgpy.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtmdwrrmrn.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtpxakwlaw.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtczzeaaia.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtcoljwtdk.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtsydanaxd.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtpjhbhjco.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkzmuaqc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtpucyhriw.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtkbmdfipr.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdhdinwdh.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtyikomzdq.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gtwpwithoc.html


<!-- 参考信息 -->