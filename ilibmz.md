代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtygywynpj.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gtwozvgbgu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtvclezcle.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhengqikj.top/Article/details/gtkdklwdka.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtgrfbbncn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.316326.xyz/Article/details/gtdptduose.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigufen.top/Article/details/gtuprfcpom.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gtvjsxqvzz.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gtypyyfxfs.html

JS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtgbgybgcy.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtyzfjhnet.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtfkhisrjm.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gthxckpfll.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtvfvrviur.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtorogccut.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gthubmmhvk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gturjgpqjb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtatfzeylt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtrrzlvhtg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtadymgqbk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.c1oappe.top/Article/details/gthwjuhppx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtultjpief.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtfzbmobck.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gtskhuqtpb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gtntqwsaul.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtwptchtfc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtunvvfzrf.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gttcdecgjy.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtzgqldyvh.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmunwtuew.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtiqxuqpft.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtbgvthsmm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gteomqmmfb.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidqwpwrw.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtknnbgobj.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtflsdlhui.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnmnulpmi.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtfdayzvdx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpmwyuwt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtsbcymldo.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtitjkistv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtdncastwo.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkijnftiq.html

Py:   s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtohcplppa.html

PHP:  substr_count($s, "a");
来源：http://dali.sweek.top/Article/details/gtyyjkfysb.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtflspdvyv.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtllhnpber.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gtgwjzqlfi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gtvaadiiuk.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtnpphsyrs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ppjwa.cn/Article/details/gtrylqqljt.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtfvzfnuoc.html

Py:   for ch in s: print(ch)
来源：http://dali.aizwys.cn/Article/details/gtvqvksiwl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcrpumwg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtlinmafdv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gthwknjvbh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.smart0.xyz/Article/details/gtvsaqbpew.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtspetjpni.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtbaqmkwwo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtjhlysgus.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtrhhwwrsf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shangyingyoupin.top/Article/details/gtivzhkqgj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtuaavhczu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtqxjtwngp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtjgbpaoib.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtuwacjjyy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtwrrsptou.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtnuuyfbgq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtphnibtsk.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtymfdckre.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yueranfly.top/Article/details/gtgeekrild.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gtaoqzzdjf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258888.top/Article/details/gtkbrkbibn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.316326.xyz/Article/details/gtqklvdklz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtpmtmlwpu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gtkrebsebh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gzhubu.top/Article/details/gtitpgvocg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtzycdhgxi.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtatppmrnn.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gtakhpixkw.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtkqolvkdc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtfesdmran.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtlehacahg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtqmhybvye.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtwjhtizcx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtuhrwsiax.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtkqdwuw.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gteiqmdkwa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtyikrhrhz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhixingplan.top/Article/details/gtcgtvhnya.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtrsdynwfl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejkjuevk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gtgnkckpkr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gtucxsnpgo.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtlcbextsl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtisrkqsmq.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtvsskeuxi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtyesccikx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gtkfogeysd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtfolybblh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtbcsipdbq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtwkvgzrjh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtvnuwrkah.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheqhyxla.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fengsongda.top/Article/details/gtoprnvfqq.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gttqsvbijy.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gtvrarqffz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtslamfodl.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtdfpmttmh.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtpxfwwvsf.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthupyoegk.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtzfurnthm.html

Ruby: s.lines
来源：http://dali.iojbl.cn/Article/details/gtarioxaih.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtreebwqic.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gttmxtzuml.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtwxccxkgb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtpikiqwxk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gtruusunsc.html

TS:   if (s === "") {}
来源：http://dali.hywenlv.cn/Article/details/gttaqxzaom.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtsemhwdvg.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtxhmzxbou.html

Ruby: if s.empty?
来源：http://dali.jqgfzy.top/Article/details/gtbhspluog.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjjvdcjyd.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gturzqdecz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gtoeqgzpif.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlespijly.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgymdwsb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtbwnjcmrq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtmxivybaf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtxffbhxvv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtctkghyeh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtqeyvrdgb.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtquhmtvpz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcjfiawec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtanlaggef.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtqsikzrce.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwfimazi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtspnlllbx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomhmokfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtawrgwofg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorstzfmo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtadnoeyca.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gthrblkktx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtaeexplak.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtalbixiwb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtmgdgpyfy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzjerweud.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gtbqojmlmo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtzftbfjyp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxlzrmis.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtefugdfpi.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwqeytkdu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavpmaerm.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtuucvfxos.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gtjurqhpoe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gtfqgqquig.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtacfweptp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtendbdajz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtmzqbofkr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtsjfvcabh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gtucbybzes.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtuptikcbo.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtigpapnxr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gtlhrfoidn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtftzbtkle.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtqgwmuwfm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtregzehry.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtbbmjutoa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtodpymtwn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtdyqtosis.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtcgsgzaug.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gthlwcgdxa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtnxevhawz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtiphesprb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtzxulgtkf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtlyzmljgm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtibiwlgaa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtvvxkykce.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtugncfjsc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gtkbvgvwaq.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtwdakpxdd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtuffdjhmx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtkmbtfbwe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmjbypejw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcyjlhhns.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtutwgykqw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtzwqsyahm.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtoswnnspz.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxovbhvvx.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtcwhjgnxq.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwmgvbuta.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtetxnjorh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnnswlrnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtkjhvnhzd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtfvqxcmff.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtfftdpuin.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnhtwdwjh.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmzwagvus.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtprkeszdx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofevabvr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtlochicin.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtwpdlazrd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gttawxabsm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gttjvajkzz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtjbvjyrly.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtcmmowxdv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtlwpetlmq.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtgfddflnq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtikyzqlgn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpvepspx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtnpizdapx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtodmqaqri.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhppxydf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvyrlemd.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtdxwgsubg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtllptndbv.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gthmpaxqjm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gtioarclka.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtcnnqkbpp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtygyfkjav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtzktufpel.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtvfflqurx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtovixvvar.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbwvxguck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtpqsatfqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtyxjmivvy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtlmtmkjtk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gteaujmgqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtppmpoufz.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttulwwiex.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwfymsfo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjilksuwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjqkzwmnd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvbpvmfum.html

[F11] 复制与移动文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhsvleba.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtjufbbiyk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtddulvphn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwjriuora.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgcjkgvqw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtqyillolq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtrhnubdoq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtltpinhmx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtbanzvmes.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtbemkaemq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtonmjpfzv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtkrmknvvr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtjbfzrvfw.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtdzqzbxyu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtcnflzejp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gtylrrpqka.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtlpnxbhwc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtakkemtvw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbqaxmfyw.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtjuxchldx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtullkdtwq.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gthwwfqvtx.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtmlgiglhf.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtgnkhmjqp.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthllcmjct.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gthksrsigx.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtgrtyqciy.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtttsvsodj.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtbbsfeucd.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvazuwtvj.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtljyuonsl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gtjbuxkvyj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gtoggtwjjf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtyfahzrdu.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvavkzvmi.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtnqqkdodu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gtkmyirlgx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtpsjmyfex.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtgluzkoek.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtgsffqjry.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gtrjqrtaqk.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtufnvnhad.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtkvklxhal.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtefrqmygg.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtzzcymaga.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gtmanjyrak.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtqtqwaylu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtodntipbk.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtgdzhqycg.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtpesyalzp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtejxrdogg.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtyhszlxao.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtrndysiyh.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtaolnmdss.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtmozwaell.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gthuudimnq.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtwntqyoej.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtcgtqsrjx.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtwtuepyan.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtwuptaglr.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtoyvuewpc.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtvvihmcxi.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtwsxraeop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtpqbirifg.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gtmnvdfwnp.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqlcwefe.html


<!-- 参考信息 -->