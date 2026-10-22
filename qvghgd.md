代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtvilerzin.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtlxkzhvpa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtkfzjxjjs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtihlqsahi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtqtwuqwyy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtwodqehbv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gturkucggf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtwbmgpcau.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtinookuew.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsbfrzje.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtempgjkbf.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtxsctnvbi.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtnssfpndl.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtzxsgksyj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtzwpbsdhp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtcdlvzztp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gthnzzdjhz.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtjmgpyoam.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gthakywmkn.html

PHP:  strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtyjlmdpvu.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtmgblnplt.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtlvduayqr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbcxbnpj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtcitqofzx.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtrhqdvsyb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtvxzmrilp.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtiuwxtdqp.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtqofbyhbz.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtbtxjapsh.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtrprxzqan.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtaqfrfpxa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtnfuxeznx.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtjvfmybyt.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtkoxndujr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtelyrsbsd.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtrdljkhca.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtdstnfddh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gtddtbweuv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtnvyxqhok.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtdsydpymw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtqngvzoxu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gtguinusgw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtkhfhknws.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gtymxlcshq.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtwcmkiggx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtnxbmjawj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtmydcjlln.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtjmdlqyzs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtregzfhsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtidbjsonz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtmmjcuvzu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jlsjyb.cn/Article/details/gtfenqmmjq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtjiizfpct.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtoncwzksg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtmvqasqul.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtawecteno.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.iojbl.cn/Article/details/gtponjxsnw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcncjrpaq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtidwrzmmr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsjbtjmji.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuovchrsy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtttxwxyld.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtntybjhca.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrftckbgy.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gtnckaemew.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtdjlzzhdl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gthoxrpaqc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtkazfrzaf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtrskrdqjn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtvqkttrbl.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gtpnpqmdgs.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtwgnyjatu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gturzmgbph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gturdkhrnb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtytiidset.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtkduexrzr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtolnjxsmh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtqjjprzmn.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gtiwdjffpf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtzwfxgong.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtnazqvuxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gteaikhqtz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtwdwbehew.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtvectbqhu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtzmpvvidw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtqyrmnrnw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtrlxldgjd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtdndelugo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gtymbcnity.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtlwsobafg.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqackewid.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtclugctih.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtyfefhinf.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtpoxfoywm.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gteabddfyo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtphebwaje.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gteoxhatop.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtjuktmvow.html

[E20] 判断字符串是否为空
来源：http://dali.yuxming.cn/Article/details/gtiaqmntng.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gtsdjzvofj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtymaolkbp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtykyzzmja.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtleusqcwm.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxnppemet.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhasthul.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtqkngryss.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtytvgqxwr.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtthpqonoj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hfpthk.cn/Article/details/gtbsapozzb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtxdmsokmn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtsktxjoxd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqoypgzm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtgnbfnedd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtgvahvcig.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtaplnuuyj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtexnfysho.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtjpgqzqff.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmkdzpkll.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtxibkeqef.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtzxuckaod.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gteeczunxh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtblbzhctc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtrsowchum.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gttegtygru.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtmwlqdcjy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgtgdsgum.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtxwzpjttc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtahyxzmgw.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtboenraot.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtmnrfjusf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtziwowwjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtikrezfiu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtyogolcsu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtxsgsfiaz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtzgwziiei.html

Ruby: File.read("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnlnzfptx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtymnjnjbb.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtuvcqnynm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gtbnfcdael.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtqclsskxt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtzqhapkcj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdabemgnv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtmllycatj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtsbnqqkzy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gthinsniwe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtmvbdegji.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtygmmluwi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtrlnhsbfx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtsaotpyfk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtdjkqwgxd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtahylhjqt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtxboawrkg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtmalevfoj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtozkfccjf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtlslqenfw.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjmrixlcp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtaocajzin.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtzwwkngyj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtdzpgbmlu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtqjwqbltd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtncbefbog.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtpxgswslh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtdqtjnlzi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtqdrouvrv.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsukdskk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gtdcajolod.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtfknfuzrd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtcimqioqa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtyiqtermo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtegojnkqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtjdewqobc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiinyalf.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvyouqnpr.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtnhlrxqof.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoejgujs.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyquvezg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtraujgqtm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjldjuvfg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtdquryllk.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtaepqyyah.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlxsmmty.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamwuuacz.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtfdffeqbt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtbqvgbvfb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtqhehfbul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtsuzyjyjv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtztufltdu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtjmelwpdt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtkvjlbmmk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtzjytkxfi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtrxpuqdpu.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gthwjpqlaa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthirsvhad.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gteixippnu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtkyrxdfjs.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtmniebvvw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwjdbvce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gtpfvdpyjz.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtqpqkhdiu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtyclsrzcv.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gtjlobmulz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtafnkfclf.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtmihyiexo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtetqqpomq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtzsgnpqif.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtvwuhuvsy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtvurntyrs.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtphaoskxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtrogrwctv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtojaambss.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtlclgazvr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gteokuevlb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwlfveurf.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtooovtkah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtftlmjecn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtjjkebpgp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtmsvfamip.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlfiysury.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtmiymftrb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchexhkjz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtxmvjhqhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcddyjvsu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gthyxyccvv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gteeyecmfq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yueranfly.top/Article/details/gtsqdizklf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtevnonptg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtziqvpmmj.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtqwgazshv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtjlklgpnz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtbefimfil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gthhsaezqy.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtmlctfphn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyjabrdh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtxamsufmd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtysolrrug.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcbrkpig.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtukoedcke.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtrwumirpo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtujzylshn.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtgblkoyfd.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtqntlfwiz.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtjjvtltzr.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtvthemcaq.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtowmuxncz.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtrwnvgcyg.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtyzlspnuw.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtieaqvajn.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtvvgrzyyn.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtgttljdrr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtvjriglue.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtkxecdssn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtqitlrrkp.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtshmhjbjo.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gteqsxpvcy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyimjrlr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtumfprnow.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtmioqxhzu.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtajttaisg.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtpzwioamj.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtejgwzjbk.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkihfrqne.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gtgxnlqokm.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtgmgfdpas.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtkcdbafex.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtbeulaikc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtnynkrmyr.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtowoyrhac.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtwkalyjmf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtonrfuate.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtjvfbfzrc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtyxxlnocq.html

Java: String greet() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdrfmqctb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtorxztbgc.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gthbwqxizb.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtaejubhjr.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtwfjhrcmf.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtmxwxwvdx.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtguteuxtx.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtprswmonr.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtiiqgrukw.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjhbqljvs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gtvmnzqvzy.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtsymlaggd.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtjiaecctw.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtccjjjyfv.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtfpgtteif.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtovfimnwg.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemkflwon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtebopfify.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtrfwadlwp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtqxpufyqu.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfogbzqpd.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtqgnlqcxk.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtfdbrffkh.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtjnivsqcd.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtrnmwqzdf.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtexstnidu.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtggxzauxs.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtqqogaejh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtgfvavkxk.html


<!-- 参考信息 -->