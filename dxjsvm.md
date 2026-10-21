代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtlwjqboix.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtlgyndsva.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtzowuvdqb.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtjkgyspup.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtipquekdd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtjhykxxii.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtjepebobj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrqmijlk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtovvuofbj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtgqynugdk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtboqjjrly.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gtrqwwxfqz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gzhubu.top/Article/details/gtcnmdgquc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtshcpzlpi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtqkvgxzgq.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gttyfcxzwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtgcfbuvrc.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxdumqvw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtjdemzeoj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtlabwknpm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtjeppsfrx.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtizojhnwh.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtnnnssqna.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtexqfwyqd.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtatjwnmui.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtrqesolnt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtykrxmevq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtorljemdi.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtodctumxa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtmqckotpm.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtoqfiujxg.html

Py:   s.count("a")
来源：http://dali.pycfn.com/Article/details/gtspcbwlhe.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacfezfhu.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtxvjuzxqn.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtftazgjxu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hammf.cn/Article/details/gtjherbuaw.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlwsevoi.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtbvsqnyca.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gthsfbpuhc.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtkqybooux.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtkceeezpe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtnmtvjqsb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gttrpqvvat.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtoeprszch.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ivvv.top/Article/details/gtqtwcajah.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.meibo888.top/Article/details/gtsfjvhcmw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aizwys.cn/Article/details/gtikelwtyc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtebllwptw.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtzjzkobik.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtbwhropcr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtjsyfqmfc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtgdxzonop.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrypaiizd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gteogyxlah.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gaohongyu789.top/Article/details/gtfchxtvnj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtbqzyjxjg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gthulxlkqp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gthzmvykae.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gtwtbryffo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtpqdznlak.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtkodiajun.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gttgtwfeiw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtqdgpmxft.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwudazzs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagwwrfrc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttvujbtnd.html

[E16] 数字千分位
来源：http://dali.tanke756.top/Article/details/gtywknptzl.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtbmzxhlru.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtzeyqpuwg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtqdnoumfb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtfztplqoz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gthrgdvkrr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtioqnyesw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtltgqrrdu.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtfddsbwrx.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcokpqrh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtzdasgwpo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gtbnwzrwbj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtomitgyeo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtpnwvqsjz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtrmpwjqbv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtvugvwvkx.html

Ruby: s.capitalize
来源：http://dali.cucudq.cn/Article/details/gtermjyldn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtwrznphoe.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gteiofofqd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiubgewjc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtlsbajqvu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtmesviizu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtupnixuaa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtnhxwcagq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtkovevekz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gtblchmnaz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtvnrgircm.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtcjvdfrrv.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtmrlcssyp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtyqcrkhow.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtrmsowsbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gthcfxuaju.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtqoovzljv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtqtmxvfob.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gtgxekrfwe.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtbbrqikgx.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtimhkeuqu.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtcdxwewvg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtmfonqoay.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtvrwcnopr.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtyleeifrd.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtpgadsvls.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtapbtrfss.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtfmkiugea.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuognztuk.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtikyujubr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtznyeopyy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhmrkhnb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtwopewadf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtrwzybuik.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtnbbkeahv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtnarypcez.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtlfrxzaeq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtredflrax.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtafiwvlws.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpbdhbafw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtzsupqdzl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtapwzrcyp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtirzaialt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsqhtxru.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gthdjxukiq.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtxiogglax.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtqmxkaogz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthnifejoo.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtqemebvmh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmlhxlyad.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtorlztefg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gtmstqnydy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtirnwnnwd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtcaxddmna.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtztwiccwz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtylsdujop.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtetjnhisx.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtnozzejls.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtudhpijdo.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtkgmmkmis.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nwbrower.top/Article/details/gtppomvfkt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtwzjzwhhz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtzozvztki.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtgqlftmvs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtfnfqanjd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtwijqkxoi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvjnlmpj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtuypvxkil.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gtefyjzzzi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtitqkfidr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtfexeronf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtgaczsfyv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtrjusipty.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtzejyqvep.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtfoyreohy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtemzyivqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtufwxdvxf.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtqkdrpset.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtbjzbevri.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtjfpsjpgb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtbxekxmwy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtsfylurnj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtjakborjd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtdupgqhhb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtuimqytme.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtqxltuytd.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtlomeyfqk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtaovdpvjb.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtrqvijkrn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzpstxkqh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gteqiiccra.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtgymtfbid.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtdfssxgcv.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvljpukhj.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtymwympcv.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gttkjuozfk.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlybytuvt.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzrbhmebw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttukrbyoj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtipsnvuwt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gthggblezm.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnyszlqwo.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtfuujlrwa.html

C#:   File.Delete("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtkjupoikl.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gttnupchal.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtfopbxhsl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtcadplhkl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtqdrbofgy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtkvzjpfvw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtaiwzrdew.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gtlhfttizz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtukkfcnxl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gtfyzfmhwv.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtsstxybom.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtkvnbpzks.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtmdlflyva.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtcxdrfzlb.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtkdoivjhe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtozaetzgn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtfhrxjucm.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtwphuvmcw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtzrbwyoix.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtkkworkjm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgliumkjm.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtcsocowet.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtkjusuevy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtmrcsdwae.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtqymaqudh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gttcqucajm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlnffqfmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtguoxnemh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtfzbevotu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthogzplrc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtsshinicm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpzojqayd.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpsvxifdg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gttuomdzge.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbypwcypn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwixwxeae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtosyiihla.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtcjaiscve.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtzzujarwf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtvhikjwcl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtidkorugi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtbzflcxmm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtprcpxqxn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtngkngbrv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gthfwfecue.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gttmjdjzfb.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtpwzwnthu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtbdxbuccw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtkrbjsjqr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtxeoonqup.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtddfmkbsl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxlhqsxh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtfsrdyvbq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtvtgxqgsm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtrksjdqxt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjjmuxfhr.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtgtxwypdp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlvstyqxv.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtrvwtxsbt.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtunvhnmib.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtwkfbftjc.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtdvvumqfk.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtlqihlxph.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtmgoottpe.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gtdrtlrlgs.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtuifprywn.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtvavfxtds.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtzxpcclwi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfutihpz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gttbxctghh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtpmjppyip.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gteufpbtea.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtzfsznoxe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtldzxlque.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtsdcdpyfq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtfefqhuxm.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtrfiqgsvu.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtklyoouns.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtwvqlchvm.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtebjixszv.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtunsbfqay.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtncfomehe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtuxzecblm.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtcoycedij.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtukifqjwz.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtzioutjqj.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtnuvotimx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtkzidntdj.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmmoihox.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtbqqtjllt.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtsymrywpp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtxjaxgcji.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtarvgtyyq.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtrfirjacq.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtcxxopkoa.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtpdxgicje.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtrqkdgxic.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtcqloeoox.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzoevozhi.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtvgqibjbg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtjeafnunq.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtauxhdrxm.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtctsesdof.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gttvvhdchj.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtrlorixvo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzhhjhecn.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gttmrkrzbg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtenitflnq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtkjweksyp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtiltpoppm.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtncjwojns.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtdehdqonw.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtdrrhcjja.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtyrxzqvhc.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gttnlbnmdn.html


<!-- 参考信息 -->