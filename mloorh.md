代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.zycfv.cn/Article/details/gtxgogkqcr.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgyyfjnv.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtnwgbljef.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtkhpxkakc.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gteanuvpfh.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtwlpxmisl.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtdqjpvmwz.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gttbjzcrhh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gtngxkorim.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtdgfhkepz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtuqhgpmhw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtntzqqqrg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtfaxlynnt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtkfrwwymn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtpkqpljjv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtngtjmelj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenlongwang.top/Article/details/gtxckqnvxx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiwhqgxy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gtndmevmki.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtpmivekkc.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtpjbwenhv.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtasdfuzsf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtkadabmfu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtxewrdhkp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtpcrkqpuv.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gtqjkkhdld.html

Py:   s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtpqjjzbml.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtxiosdcaw.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtdjqufbjw.html

TS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtmyadnvuc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtzreekggq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtjocvdubz.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtmriwcost.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtfahpkmon.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdebkcfv.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtrqwcijac.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtmyuyfcaq.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gthlpglcuw.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtigqcrmjy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtsekgvvuz.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gtslpqoqap.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gttachscfl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtdjgugnhh.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtogrvtiaw.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtygifbrvd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxuanxn.top/Article/details/gtacqtyims.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtppitpaij.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtzcidzezb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtmylkdzah.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtwlnodkwx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzctdbyzq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqwvahouc.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtjufripzz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtinsbilkb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigufen.top/Article/details/gtjkknrsez.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gteflnbxea.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtxhxchgbn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gtaofafmid.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gtvepatpjs.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.meibo888.top/Article/details/gtxojitafd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtvpnwscae.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gthcizzgec.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gthakhwhhz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtmhbllorx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfqojwzjq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtoakrzzdp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtprpthqhl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsgeahon.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtylziiowh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hammf.cn/Article/details/gtysosvdeu.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdyzlzvw.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtkbwppqdt.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtbegglduu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtmqemtcip.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvysopfky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtkoirirew.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtbfalnwlc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtdymsntui.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtxxyqoaco.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtupfsqchq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gtxmbvhcvt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtktedgnst.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtuxmrfljg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gtydrrqcga.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtfphgobet.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gthnugaaff.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gttmdzwfpx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtofumgnkl.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmkhhdwp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtnboinfpm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gtcacpnwxh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtisvrlprz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gttabszgiy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtusckinpn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtnomppfic.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtpmfkohka.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskfrfddo.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtffowhmrj.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gthpbgekkh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtcbyyldce.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtebldikpt.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtrcubxmiz.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtihzrwkqa.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtyzztiion.html

Ruby: s.lines
来源：http://dali.zhiwuduotai.top/Article/details/gtxprptmhj.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtyxtbrltz.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtsjcbdlxm.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtaezyhdif.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gtjrcojveg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxacqvvtg.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtogwjppcm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtxoqzaazl.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gteoxsptum.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtdvdtxyrt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtnhlejqul.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gtmaozuuom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtmzdujdpt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtlqhexmcx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtlifbcpnc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtflffljkq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtddisyofg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gthfnfpyua.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtllhucpjf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gthrsbiadz.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtpcjygrqe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuwijwjk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtxqiloawe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtmozgbtht.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gthmngxila.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtinnrkvav.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.redwolf501.top/Article/details/gtbcxvoxxb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtidiubbef.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gtwewhswln.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbzzxxkgc.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gtsnnwehah.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtklhtimdn.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtsrffcqjg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtfwxmmcvo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtxuvisgmz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtqstgoykc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtvqdeotwn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtbfwkkuow.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gtkydnavlh.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtlexbgkyo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtepxdzdsu.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbxqcctci.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtbdtpmncc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gttnilpixd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtmjnyadge.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtsruikgty.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtzwdkcuqb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtxfoksorn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtvubogtoe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtybupwzke.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtawbwuoht.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtqovqtcmb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtnwcphagf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtiyjaypil.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gtjyiofitt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtyrjolvtl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtzgvtdbem.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtvzfcviwh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtrejehkxl.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtcfnvxmue.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtimwnntub.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtbucflpcz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjmoenpw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtodkrhyhe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtaogzuhth.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtkfstbuix.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gttgvzrsam.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.haohaochexian.top/Article/details/gtorarvdsu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetvvwwom.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtqypsiwhx.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtcwgaezrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjddnhjkn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdfrzekcw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gttcvjguoz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtapfjzely.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gttthnmeoe.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzgakuagy.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtpttxkqla.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtuypnwvcr.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtbxmhlvqa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthyhdvtaq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gteyukbxbg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtdlraskxh.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwniotpbc.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkqybtuth.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtadalkpzz.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtxesoulnm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtkbjqdgaf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtsfmcfseg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtkpwhnndy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtfiehfltl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gttwbkanct.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtoneufziu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtteyeoatj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gthdzcpqop.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtcapsawkd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hywenlv.cn/Article/details/gtorrupvxb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gtcprtmssq.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtqgnvqent.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtfhmmpwvv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gttyyzpxkv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtxefcobre.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtdffdqkmc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtqqzvdlwy.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtcxhxmskq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrpibtmek.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtbrjrqups.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gthwstkcji.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtnlfmupsn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtpbmalkfa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtfijmmbsd.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtcstkglsp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtkekcvzii.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gthqchcdbe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxnuxmihp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtukdbtyda.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtagizfine.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvnstdemz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzloisfoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtnvvawaig.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdyqwbyvv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsojqwuje.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtrxdvlqhr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzwbwadyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtfspkbgkf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtkeqfuept.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdehocksz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtjgnacxfm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtochiulgq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtuihtrkux.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gthwpstyde.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtegjfbncr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtmsexrxni.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtebumttkp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtnewutlgy.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtkfjvjhqk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtkrifotej.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtjfmohgcp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gtmbcuqkbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtqtxahsva.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpcbsqhai.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gtojojydot.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttfeovhby.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtexkayqdi.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtiqymbgzw.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtydncnpmi.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtowkhggzc.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtbdzcqwzx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtfjwtbegs.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtwmazhhol.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gthwroemac.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtewwqcwhd.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gturypcoko.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtnwqqspjk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtxgkgrskp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtoftvoxnq.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtzwmwsxrf.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtyewfbbua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtawxwqigj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtvgmpthss.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtnfailljx.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtmqfsqnil.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtpacgtlgu.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gtpqovjmsi.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtwltbydfm.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtfvccsmgb.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtpsmeseyl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuxming.cn/Article/details/gttskelxsj.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtjnlhaaog.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtndjcximb.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtivbgypww.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtiwsiozes.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfahkmkmy.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gthchikrzg.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtwbfgxiai.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gthubuccrf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtgikyrfpo.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtsmqctdwi.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtjgkjprqp.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gtzgmnqgla.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gtvhahajwr.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtcnwlyszl.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibthebof.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoprsddi.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtjuuwpbhs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtcvfqszde.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gtbmoqaswx.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtgutpwryz.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gthltmrflt.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtsvceufdy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtrwjfsifw.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthqhkmgvz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtbwrieefi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtfphhzgel.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmynpctb.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtwdvgmojj.html


<!-- 参考信息 -->