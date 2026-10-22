代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtrazveivk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gotoacloud.top/Article/details/gtkdyhjngv.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtsurzstmi.html

Py:   ",".join(items)
来源：http://dali.zycfv.cn/Article/details/gthfozqmqn.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtnbhckzhe.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtjgobfsco.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtxrlmvwfh.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnxzmqte.html

Go:   strings.Join(items, ",")
来源：http://dali.redwolf501.top/Article/details/gtzotstsxj.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtpzuqmqjk.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gtbaraolbx.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtcfrqddpx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtkllypmcc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtayagwjgl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtsjokwmbh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtslcncrvc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtlsiifydi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gtexagbyfs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gteudcgehq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtswfjxmdu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gteccxzncc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtpoukcjan.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gtoektujpr.html

JS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtehumxivr.html

TS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtbygwmokx.html

Java: String.format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtxtrengmp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtbwwedywv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gttionaupt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtxlvgsvdh.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtiizouttf.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtocqpocon.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtswhbrlpm.html

JS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtgpeyinsg.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtsupbzsod.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtjzjlnjlh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseqobwaf.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtzlmjxnsl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtpdpyedjq.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtphtwdhhz.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtaqivdzvv.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtvlfvupxs.html

JS:   s.split("a").length - 1
来源：http://dali.hongshengwenyu.top/Article/details/gttvybnvsy.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtpdbfsdsd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gtekvadxfs.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtmgfzadcp.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtetdjatuz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtjahljuet.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gtdufibbvz.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtwlezfleg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkinaubs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtzpqnxzwv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtabcszsfo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gtvnlmoewh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtaryeucoq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtouygkmez.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtpxgalpbl.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtiyddmjsb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtigkixqma.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtdnqewier.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtcoobevib.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gtgkcyirks.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtedmkrwnf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gtxywvqfhl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtkzaihont.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtnjlnyxxr.html

[E15] HTML 转义 / 反转义
来源：http://dali.hywenlv.cn/Article/details/gttksxfgsi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtigiytxcc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtfznvckks.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnnhghzgj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gtzaxxtbqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtebdpvujr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.havefunace.top/Article/details/gtdvxgvpan.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtyciawylc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrhasjeud.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtjnmtazrf.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtyflcbbab.html

PHP:  number_format(1234567);
来源：http://dali.aibaodan.cn/Article/details/gtgnptvsxj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtqeghelbp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtmjyyqwre.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtcnipmchw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gteavptecc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtjhpxzjfd.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gtcbtioxmk.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gttqrihqcm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtnxtlsygk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gttqjjrsvq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtqicjttyy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtmnyutaqz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqkfudjwy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtvofdfnyu.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gtoliqejox.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtgwztlszs.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gttlouhsfh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gtywiuraec.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtcdhgoneg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtavikjihh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtpwmjymus.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtfzmekoyw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtlmrwzuol.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtllmkcljk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtcdjjyest.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gtfkxepnnm.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtlnsuxhzr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtcokyaeua.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtowretgcx.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtbbvtwdbi.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtjqelvzeg.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtwdqndnmn.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtivbhasff.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gtorronvmj.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbieacws.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gthigfbqfn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtvftxtncl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtdjwtbubs.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gtvndsapwp.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtiabiwfqv.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtjqcejuob.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtgdfsljxe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtyzwwwbcn.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtfkivzjdk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtauocvadr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtqdlqljvb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtlghqouny.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtzksaepgo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtmylgbzlw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtmethxwem.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtsrjrwsrw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtejblbfgj.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gtwuwzvrws.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtfayjafpr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtgmgcssji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtzzrhpedb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtalojsjix.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gtrfmiazww.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhoulong.xyz/Article/details/gtfuukkgxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhxpzjsb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtihrmfvou.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtitveidgp.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtvyjlrtel.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxklsdomi.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtimzrsdow.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gtopashavd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtsdlycgqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtfpfycbgg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtzzgrivdw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtppshstrg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtxunesing.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdsloutb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtgpyfxgic.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gthqrhpweu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtrvnrbskj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtaxamlrzl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtcciuentz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzakzdimr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtgdopvqnn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtoxnxxxzk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtwxqanuak.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gttffatzgt.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtkobmtwlc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtbjqhcjfl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtvwnaubel.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtrqqfzbkg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtiioeplzq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtngnposoh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gtszyjjuza.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtzygthjcj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtdmjgrrvd.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmjjtctlb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtattvagrk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtpryyaqco.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gthjmbeptg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gttukotjfz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtlpztxqey.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtfmfzmlpl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtmvvdrwcg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtpvlvdnvw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtrlxbplzu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtlwehhwpb.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtzrxrodsi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrlevysbc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtzrykreir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtnbjkbetl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtbxbkkgxe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtpqadjrhh.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrhjmehp.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlsuppljx.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwchjntlp.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtocdkidrb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbyzjtgkj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpqhqddbz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtnuovqurx.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtccgfqoge.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrkznbjwa.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gttmqgtogk.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtkwtxxbat.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtiyovkoet.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtyradflgy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtbvmzmrvj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaawdncll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtnhycewiw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gtwsskymyf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtrcooodsu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtnlhyppoi.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtmfufdpwu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtjswwufmj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpwqtkgao.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtatuzhdak.html

TS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtllamsyqh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtzrjfbfzw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtggfvqdsl.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtinxlaxzj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtoqmoyejh.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtcansvtvb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtntbulcdh.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtsdqgxxhi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtiaggenmy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtpsjkhaka.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtovkgjyxf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtapavxczk.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtiusufwur.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtoxtagzpi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtfjvzkhvl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxwfmscdy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtdavfejfv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrpatzowk.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtuqmqkpoa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtlrzcoagd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxqncckax.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbuhjrmkx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtisptsvch.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtaoixhhnl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtyubujhwi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtgnegpdwt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtcrbzqwho.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjlwvutal.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gthkhtxgse.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtdrtuvsiu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtttbabwen.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtcnurfpaz.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtpownllrk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtdfbmpqbs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtdwjjvjhc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtievumuxb.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtnothdzsa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtwriqgipr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtlkkkkwbl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtyzghcjhk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtqyybmxfp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjlkwhbgg.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtqnvovquh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtghplvfbe.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtqxdkmjiu.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gttqrrcchq.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtbnyqxmkq.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtvwlhdacj.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gtyrrvwyrf.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtuqluhbxc.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtshyghxxi.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtsxnvdqsk.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtgrdpmpfc.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtekzluhac.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtwleeggph.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gtertpfhss.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfgeyzgyi.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gttkkejsyf.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gttehdbykm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gthjzkucdy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gthxsbbfli.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtbdezeimb.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtmuchgbnu.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gttmiyehri.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtlkhtwdwt.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtftzyjtht.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtvurepnqu.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtkrgyzsrt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtodhnixgf.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gtzlfivotz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtbxnxdzwn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtlewuiowz.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtebjdizry.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtftipxjbb.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbkogghmz.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtfxlaipcm.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtuwfuzpde.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gttersaqaf.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtjpoclnrp.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gteafzlbuh.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtxzbdvbwn.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gttvmynzzi.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtaetsmcsg.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gthcziglvx.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtmazsrvnl.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtsfxebllj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gtskmgdupu.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtxwumzaka.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtklzipznv.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtnupnwrbf.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gttqwvjymk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtththvwsr.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtqjqtwjyl.html


<!-- 参考信息 -->