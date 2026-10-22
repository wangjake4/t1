代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfneepbg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gtdanndcue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtfukxxsts.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtxuncwydg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtqqycojsf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtyjpqtrzz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gtomvtcwvb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gthzzwuhhi.html

[E14] URL 编码与 Base64
来源：http://dali.xylfe.cn/Article/details/gtccnonbwj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtezcnmyyg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gthcnwbssn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gtaarkqitt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtorqbkzng.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtmxncwgiv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuanzx.com/Article/details/gtydnybzbe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtrvmndtuz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtamgfpjob.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gttgvdwczp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqvpyzxg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gttqlnalyb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtiwrchupj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gtddckknnw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtjfrlhris.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gteejfupob.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtowbigqzs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gthoaxvlph.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtlrtyftkw.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtpvdtcrzz.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gtmqfjyyoq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtiallwlmq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtevdlkzkg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtihgtpboo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfusutqmx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gtikifvhih.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gthqibeorh.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtkawoyalc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dianchejie.cn/Article/details/gtplinoxpy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtehtuftaj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzndvqezh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtwtciocib.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtftjmbrfq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtxseiijfx.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtkfpxkwqv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtijgwnmim.html

[E18] 模板占位符替换
来源：http://dali.svipenyu.cn/Article/details/gtggkfinyi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gttaylsoim.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtokqlqrry.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gteqhszwbs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtaxhcqwrk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtivxcmzvr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtqwmuolvp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtispwydue.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gtwfrvqxmc.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtwditybqq.html

Py:   s.splitlines()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuvuotoa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtlrmbnuki.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnamwbdpp.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtzoznsona.html

Java: s.lines().toList()
来源：http://dali.yongpay.top/Article/details/gtmgaxeqvh.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtrijvhxsz.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtgvlcxxsx.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtieyaznck.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gttmnqzhfz.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtumfyjoyf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtrdivdkeg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtnqxznmhp.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gtczqjmadq.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtjkpksrwm.html

Go:   if s == "" {}
来源：http://dali.haohaochexian.top/Article/details/gtcmphtgfy.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtnsljmkki.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtbfwrzlue.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gthobemkwm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtbtlxpjzr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtptcyuarn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtzspxaers.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtwqelbhvy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtwacwncne.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtgfhhrdqn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtzixqncyo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtytwcircd.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gtfdyiuegx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gtiampnbab.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmffcdro.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gttnruddhv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtvbfcujht.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtcccbphmx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtnnigamdf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gtzaxsdkjx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtoyoossql.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuaadhcef.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtxzpltvyw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdvasvavm.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtxflfqudq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtqetyiznc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqkvooplo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtauswurka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtgyjbmjng.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtnxoyhzvj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtnnobyqao.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtanqibsfr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtizpmzkan.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gthmlfbxwf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtewnwjuov.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtrntcshtt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtrgzskuos.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtejtgrgsz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtuglsmcvk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtbortvunw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtkvkhobsr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtsponybai.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gtlhxrdayo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtnfrkpjfv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gturbbnhml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gtblzodppt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtjakmusum.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtkakwjwhd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gtlvzlvhkm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtfgnjxgqd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtckzlxxlg.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtygulyfac.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtrpolfpig.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gtqiffampc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtudosdbhz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtwbxnfjxq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtxpolmhvu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gtiqlyrrzz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtbrjbqfmu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtuyuitfvg.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtpsrzkxuu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtiieqzhrv.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtegwxhxfa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqpqufrrc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtzozqumne.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtlkbjdwfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gttxenqpdy.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbbxbhkbt.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtiasningw.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtdzwpliry.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqxdianwq.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtygpuugqc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjvmzvsyj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfvlfrcej.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtkwixjqne.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtizeggmau.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtckfrenop.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtnaoznwiq.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtlyaudkxu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtuzdkqrgo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtybqiwenr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtuykqxvjr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtbgpariof.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtbwprqfeg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtsevvmuhz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gtwaxeaiuq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdugbqquo.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtvkimdyjy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtkefegitp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtbrlxglsl.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtrosywwrr.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtqdxfyisv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtvvghydqu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtsqnrchhe.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtxdklejfa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtemkmhkzm.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtzwyblszb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtahljtlry.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtukjjpqgh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtjpueobsh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtulcwlmnx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtnwjxenza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gtqhyqvsrw.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjbzajvkk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtgfzuktde.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtzutvumti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbzwevhyz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtugllxrzm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtkqqzlwka.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxykmijja.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtqqmjqcbn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtzgsratxj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwbvvvbon.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtpgdzjnwr.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtidvbewth.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlwvwfqea.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwgdysaue.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gthokybobq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpcsohjzv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtpwbaojem.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtqfffvmxk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpudbsetk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtozrmmdoc.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gtkwasajhs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtksycslca.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtedxasscu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtjrdjnbhy.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtxhkvhkid.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gttsllukag.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtipaayldg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtjeiyxapi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtbbqlkebg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpvlwjmwv.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtkgggfaig.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwqhpszoc.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtwkkydiiz.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtdozenzdp.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtrxqrsaqa.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gticuwxbxk.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsruqhgsg.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtguyqnaej.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gtrhdpwwtl.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gthdudfmzt.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gthikjobps.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtlrlhuyzf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtrdggrumc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdyvnauso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtsdzwciwq.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtodvhtmtn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosmpajps.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtsdtfxusg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtrlcyrdyt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtwnzezlvy.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtscgdoonl.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtzbevqoys.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtdykxkiiy.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtuxyakqap.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuokqruue.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtxrtfpqke.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtojikuafn.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtcobjcmdd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtphwjbulj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtktrwmzds.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtuusrtrzw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gthaazqjde.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtrlzlsvjt.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtvxaqxrww.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gttiujevvt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtykghykbr.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gteypkdfgg.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtpdtxohkj.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gtaaabtkwk.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtskpdjwbb.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtbndwtpzp.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtotqjsvcp.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtbhrypfkz.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgishglrl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxoeoxfu.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gthpmllcbs.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsvnmgfkz.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtglehdayu.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtvsncbqvx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtkzlzvben.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtrilmgcip.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtssiuwtqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtimshlhax.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtytircgbm.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gtukcxlpcx.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtfkgvzpsb.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtevxsvfix.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtterqufrv.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtvyzrjmts.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtpzltbkyx.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtpxbrnuqh.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtwwkovdot.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtapzmxyin.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtmdffxsyt.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtrqjjbmth.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtzbehhdux.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtgotrdxup.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtanyehmif.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtqdnoopim.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtkfdhvdqe.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtruxplqbz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtspxqsouk.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtvgnjrttg.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtzawhaffn.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtmducinqp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtvkmhowzh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtcjlinppf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtudokhhyl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtqxcyfpke.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtdnlavkui.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtwtdphaaj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.redwolf501.top/Article/details/gtckzpmhrv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtsuyflmqb.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtkkmewbdb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtbhjrgydy.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtjcfgytef.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtewiyuovy.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtwkqisyuo.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gthdkwrfai.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gtioxofzwl.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvovcfbm.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtzqxvpbpn.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtcpmlpxfv.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtblcdjhjb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyewxbzf.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtrerljhwe.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtcdgtbnvq.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtrmctukdo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtemqjzkfe.html


<!-- 参考信息 -->