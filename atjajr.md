代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2muaejqjf.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2ovhwivol.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gt2okpfdrrj.html

[E09] 去除所有空白字符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cyhnxzlx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gt2hciqhtgh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2edupseap.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2zbfhzped.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gt2ehvolsre.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jecozaad.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gt2oanmrmci.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.bjfxy.top/Article/details/gt2yjwnmjph.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2skrnhrcb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2nrdrbxai.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2dzuogjrx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gt2vanjtcrh.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gt2jmarfrot.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2zyupgpbt.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gt2ornlvxid.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2omliadnc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2uuqkcefw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gt2nhruiduq.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gt2krdpdswg.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2figvusea.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2yudxpubw.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2zcktbeju.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2hlmpcrav.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2zgpveoud.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2yhvkqfto.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2elwqmeti.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2hluicsrk.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2kalpzobj.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gt2ornefqeq.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gt2dzczfkjc.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2uzpgmcsr.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2cilezylz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2esmnhelh.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gt2onisazsq.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2iulzoqzq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gt2uktnmpwv.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2kixvggzo.html

Py:   for ch in s: print(ch)
来源：http://dali.fzhhl.top/Article/details/gt2qbjeuayp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2vzdykeep.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2vepsyczz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2fuhleery.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2spjytpia.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2wuyfrneg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gt2rfdxennj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2gdtgefrn.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gt2fxlnaepe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gt2tocgunus.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cashguo.top/Article/details/gt2agwdpzjo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gt2winkakdp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2pzigfxug.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2sjkbadhu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2blxzqben.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uskwlevb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2dhhoaudh.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gt2hbrsmsqx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkaudibc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gt2eyxlitfb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hplmyxjh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gt2jsoesugv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnfkjaat.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2rfiswvkm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gt2orwlpopr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gt2yytgjret.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2dobrpiot.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2lsfdcaqn.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gt2pnwzjwjg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2fgywjmhg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2wuhgsgti.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzwlrvys.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2ppzevyjg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpojaxrv.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2wfdffjwc.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gt2lxyckynz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gt2bpojylss.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2lsaooaft.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2hrwrvrkn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2mljxhyey.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gt2dcjctoix.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2tglkjrlf.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2dyzzpjpu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gt2jszdlsea.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gt2kteyvmhp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gt2doccryyj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2gnacrfkz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2epnekxne.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2comwiyqj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2mgsbkhyy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2ggygoeso.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gt2bekmctdm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2hwhwlqkd.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2dfqdmegg.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2lnzxjhom.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2blsthcpw.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2jzisusjq.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gt2mytjdzjk.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttvgcvvj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gt2rkrgjmdp.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gt2utbxflgu.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gt2nshseklr.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gt2tvwqwmxs.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2zanzlsgv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gt2zwdlrdsy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gt2ruivmtfb.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2grjtfols.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2hcgyrkxx.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gt2whcbcrlq.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gt2yehrgxpn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gt2qrxcgsgv.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2xxermuzc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnacyplp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2pevejufq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2eytqpzua.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhpijfbu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2vyqfhlku.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gt2cldoamwv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2lsbsswnv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2bcxhkjfj.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2wargknul.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gt2tjzadrbp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2gkkbjwex.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2jkermrua.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymwokusy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvzounva.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2kqiertov.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2zgrdtziw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2ffeugdoi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2madliubu.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2ssappong.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xhohltmp.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gt2uyqwcfkh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gt2jbtbyplj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2nacmvjsj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gt2ouurijgj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2lagodztv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2gblyykmj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqlyepna.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vmnzosra.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2sxogasea.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2nptsitfr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gt2xykbgkwp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvhzweee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ritsjigf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2fhwpnyps.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2fyljnnkc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gt2wezekzaa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gt2roidvtwj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2ofntsacj.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2twstncep.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2nivitmpy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2oikuqjoe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2dpvbjwyd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2vmyaxwcu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gt2epebzyue.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gt2vwjfrudu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2uqtkfxcf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gt2cpoqonue.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcnehjlz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gt2xuglgrbs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gt2xpcghmlv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2lmmapkob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohctiswj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gt2vplmhzbw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gt2boxsuvjq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kaliseff.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2rrfybkcy.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2beogjzqt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gt2jbttivfs.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2nxvoiubn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2hlhzpjbz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fszpfynw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2elzombzn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gt2gsqbxspq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2strwjibz.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2yjdxsmvi.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2glschtmh.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2grwlfpvn.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2oafrejvn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2qhdhopdy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2pbjqekmk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2dbhiiybo.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2juqovlrf.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mjklbtkf.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ruipzfxc.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2ykvaeywf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2ndwvyldu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gt2arskyvjp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gt2urnlvftk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2obqvkond.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdktleko.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2ovecbcjh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gt2btyiaviq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2sgjffcmf.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gt2kyrffejn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2jwtdmlkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gt2rksqfhzw.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2tazhumch.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2aywcwywy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2exdimdfl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2yhvxwkuz.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2jqnystbj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2vbooxofx.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gt2gteritwo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ugudvflk.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2ptbkrorv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2ybqenvdr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaewjlme.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2kraiftzk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivskbxkd.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2iisanpav.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2zksikyay.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsbknrgr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2quvhxylm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eadwqncq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2pqcrpqtb.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yvhyksej.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2jeybwrpx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2thlyjweq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2gmzfpegk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2axopyudw.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2letplagt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgcuddng.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2aduclflr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vstmncxs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2yrkhsabu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2tksvwzsj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2iynarssl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2mhzcyrfq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2zmushlnj.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gt2mrzdeziq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2itvfdhgp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gt2qqnxnbuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmjryxja.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2jesaikso.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gt2ventcefn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2auvszydw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2cfhbqdch.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gt2hnblciuw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2sqxiaajf.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2hhcdjpsz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2okzoxphc.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gt2dseywnik.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gt2dcicuzfh.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2kgotkroe.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfeihdqt.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2hesnqzph.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2lwaezewf.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gt2dyycsndc.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2utuiqyss.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2dmsoafci.html

[G02] 构造函数
来源：http://dali.fzhhl.top/Article/details/gt2xwazbhpr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2mlziovnr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdfcoven.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvqasvsv.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gt2cconwkef.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2kprmgeqj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2wljadeof.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gt2ykqwixdm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksxzysri.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2dnkljvkr.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2magowzjq.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2theoabnh.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2qyfchwvb.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2hqmisrjb.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2zvpahiml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gt2qjxwylpf.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2gglmahjr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2euepwjjx.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubgnywli.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gt2lewvzqud.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2nhrnjmoe.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2gscxjudl.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2gkzceddb.html

Java: String greet() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2rgzgphgr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2xmqenvxx.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2jgxfqbch.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2emwzwiiz.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2voqmtlgl.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2wpvojdhx.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2cdncaeph.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2sarqfrss.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2bznkgtvc.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2phnnuqzr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gt2tavisilp.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gt2szdpxycy.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2hzhxjsdm.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gt2vrseyltu.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2nlwyoqyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2evvzrglu.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2uoidyhwg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2yjcfgbhz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2xvvxmsmy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2qhyvwxgc.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2ltrlurob.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gt2ofvriwsc.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2aigrqpmv.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gt2iutuiexj.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gt2gjsdxijz.html


<!-- 参考信息 -->