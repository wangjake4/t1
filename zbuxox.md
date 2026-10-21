代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtbhvztwnt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtvvmzwnsk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtzortsyjl.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtqjpxiepb.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtjpqxhpdq.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtqwhlykjr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gttymtzgam.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtmumvpxxs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.c1oappe.top/Article/details/gtnpdzsdmz.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtzwcjkhdv.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtdnbtijnr.html

PHP:  strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkqkvebwa.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtofwuogis.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtxscmmnsh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnclwnxm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtzhrkodvl.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gtzowcxqml.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtfayulhvs.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gthanuliyz.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtezyvzakz.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gthmmtvaam.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtfusrkqfa.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtokphqdnm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gtpxhvivgl.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtbbuhhngx.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtkosbsktp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtonioiinu.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtihvojmjb.html

Py:   for ch in s: print(ch)
来源：http://dali.zhijiandao.cn/Article/details/gtwxkxwpkv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtdqytjqpr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gtfczvcwql.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmckozhor.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtdzpvzpfh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtjtvqzxmo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtnkleueuw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtshktfmxp.html

[E14] URL 编码与 Base64
来源：http://dali.iojbl.cn/Article/details/gtkldgtgrd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtdnuydsww.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtqqkqzcgd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gthpresgok.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqghtxdn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gtkpgnsdnk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtmnbjsuoo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtuhasuzmv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pycfn.com/Article/details/gtjyetghpq.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtvwumvmuj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tianlin.xyz/Article/details/gtaqsmiaii.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.iojbl.cn/Article/details/gtpnwvntta.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpoezcmcm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtlvpzpzyz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fengsongda.top/Article/details/gttnrrlawd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtllppszei.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtdaozflce.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gteqsmawvq.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gttmqnzmzc.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwzqzfmz.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gtyxmznxkv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtsjogjwdv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtzdqvmkat.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtewfpduwa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtmlfvrbwi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtnxidwhiq.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgufenzy.top/Article/details/gtiwxxgmys.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gtcodfvzyl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtlbfmvtih.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoibprmm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkuqtjypi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtbsassykp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjgdrbcbu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtxbhekcwg.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtiwpqeskd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.bjfxy.top/Article/details/gttzxzxtkg.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gttrsvgcba.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtdahwdwdw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtbjppcckk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtxfynofhq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtezeszqkj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtyousrupu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtkwsyfmxp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gttqrkelyh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gtnblpicix.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtljxnwxhg.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtasjalgfz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtlyfqhqxt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtkqwgpdus.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhfwjiok.html

Java: s.lines().toList()
来源：http://dali.bjfxy.top/Article/details/gtztijggjj.html

Go:   strings.Split(s, "\n")
来源：http://dali.yanxiufei.cn/Article/details/gtfbhnkyvz.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtorwgyblr.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtrlveaaun.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtveqmcxik.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gtsvqcajlw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtrnlcoxjx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gtjnhmnpch.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtzqwwjudd.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkxqiogvs.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtyjseomew.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gtpbwdphvw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtsyubacst.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtmhlthutc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtayvumoen.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtgxtkkpjr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtqqvsaawm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtgkzqkuly.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtyvyumeok.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtlbpdzlmp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcwpgsbn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtrruvnbkh.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtadioujlr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtfowpmesd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtdbxdznph.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtrqyjjrzz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtvciafkyk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnljagwya.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtcsslbmsk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtahwzzord.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtrvlininw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttsdoekne.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtgagsagez.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbjtujijv.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gthmrujeac.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtbksqkbvg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtrmgxanjq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gtjqmhnfei.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtbrifkple.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtifijzmdk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfgrvaek.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtdrqevnrl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtmclpilwu.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gtacfraakt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtyqmhgwmu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtpadhlwgc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtjjltlnow.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtoclnnjok.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtfpqzntax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnlscjrz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtsmxsxhsj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gthijcdnlq.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtmsbcojnh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gthiwbyudm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtwwxjvcmr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtyulbfyho.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtldhrklza.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtktsjsggu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtcudzetho.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtyiloeeqn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtwwdhugbl.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtjcadsspv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtgesdfndb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtmkakfsne.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtjarulckx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtcisonrbm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtyvgveuav.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtdyzrbhuk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtujfzccze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtbpqqavnc.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gtrdkxikhu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtsorgylfz.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtoyhhlwil.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxibuzbdx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvrompgda.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwfeimkk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtzspprfmj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuawpudj.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybmmwnld.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gttgfzetiv.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfwqbluua.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjfbsvap.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdwonbrvo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gthfxkyfnu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtqxfnqdlo.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcderttfu.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfojaqwkq.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtvbuxarpn.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtlbueuuhd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtuxzauuzb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gtixapvnsh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtidmtjhpl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtqnwjekad.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtbbgrsdyy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtggksjcai.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtxrqwnufw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtvajtucmx.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gtrrjprkmj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtgaballje.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gtkdtcfkgi.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtklejbznt.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtqpsmzjyl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtyripylxu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtegemphzt.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtpbdfgmjl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtzfnjwytl.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtadigzkdo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjokotqke.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgxtymxxm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtwsdpivrc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtlzprrzng.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtscdnshjy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtlabreqrf.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyqwaeca.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtbgugpyuz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gtwpmykhsz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmaolbthr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtnbhhytlk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtzyobwyyt.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxiyjzty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtmzgduvvm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtetgtpvep.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrvwhastc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtagujwlgo.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtodrrlqos.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtqazbwckg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtwltoapwh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzqqhjusa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtrlxihfpi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtbbgrpvwg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtmecbpixj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqgqsazc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gthawwbusa.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtuqdxfcli.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtjliclimk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gtcoclropp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gtuvazdgny.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbhordmu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtmhghnmhb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gthhbsfpfa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtrcnvojte.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gtpkqeocik.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcikwbfe.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtlwczjgde.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtavkaelal.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtmoauxevw.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtjxbxlvqj.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gteevuzcbf.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtiqgzbexu.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtwqfheviv.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvabtrrwf.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gtobyddiut.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtnjwfjzti.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtovjjtokn.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnlxtqjuf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtwarnkxdj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtsiivwkfr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlmfrxcov.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtqjtfheqe.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gttppmheui.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtnokwcocm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtfpqqauah.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtvirajxyn.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtmnqycizn.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtkdwxcztq.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtxgdfeltg.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtwiecmjlk.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtwmwmahev.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtdnqenahh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtlseohewc.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtiyaaolnb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gthrzdjvqr.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtgfbqbyrf.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtfztbiano.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsejhbrkq.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtskabwrwq.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzeivalhg.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnxevfafc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtrxnkdxzk.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtdakbxuzg.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtsqrdvmcj.html

[G05] 继承
来源：http://dali.cashguo.top/Article/details/gtvvjdtstc.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtwvtfzihe.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gttzcgvldh.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtrgzhriki.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtqudfjyhc.html

Java: class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtrtokqtgy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtuwegseoj.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gtjowqtjbm.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtrazjirsc.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtntujoegw.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtkttwvqbm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtzzqpwrrz.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtdauvsdfn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjicjxhbl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtzyomxowq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtjqfgfjob.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gtpdiwkcri.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmraetrk.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyypkwxk.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtgnbmgihk.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtzujdgszp.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtbuzdiisd.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtqhevpcby.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtthigumuw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtjdsjnlsu.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtpecegkhf.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtjtkcwckr.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtunqcxzyf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtaaadcahf.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtxlzmchrk.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtvxfbbdyh.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtoiorjlhz.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gtxntfpdvj.html


<!-- 参考信息 -->