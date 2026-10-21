代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gtnvmieqzk.html

TS:   s.split(",")
来源：http://dali.kuanghao11.cn/Article/details/gtlztozvko.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.chenjidiqi.icu/Article/details/gtucsycldy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtfsjnsphb.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gtynowtpyl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtiekmrkjx.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtvfwqveav.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gtkugqcywg.html

PHP:  implode(",", $items);
来源：http://dali.guowangkeji.top/Article/details/gtksfzypfj.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtyusbqiug.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtlecsakhn.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekihqfqt.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtoxxrxxce.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtiivnnnzq.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtojvvtyrx.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtfaggxgvy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtilagpgjo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gtrvzknfbj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtumnfwkrc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtfwcismqf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtfnckkycl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtmelwgayt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtgtqmcwoz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtzocuummw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtpnsghmds.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtammnhrpo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangdashe.top/Article/details/gtaugbpcsl.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gttfxwxoqr.html

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtervxhjed.html

Java: String.format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtskvogewc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtyamdmihu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuytydxv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtmysyshle.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtrcopzywv.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtsksqxnzi.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtyysuhziw.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtyykoqsry.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gthevgrxjy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gtnbklbcrj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gtsyfrezel.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtcqvvesex.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gthznqfkeq.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtauupcemi.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtiabtjynw.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gtafdtylbv.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtapnkurbo.html

TS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtqkmvdblm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtxqpnrlby.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtiihkjqji.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtvwtjffue.html

C#:   s.Count(c => c == 'a')
来源：http://dali.c1oappe.top/Article/details/gteqfhsyji.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtragyblxx.html

Py:   for ch in s: print(ch)
来源：http://dali.gotoacloud.top/Article/details/gtotusxexp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gtxvbwwdbn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtifhhtkms.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtlmhgbpzf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gtaroklhvs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtoldjpvyk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gtifebfvii.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gtddbuepdn.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtbngezdvp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtihncucxi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtakaiqlfl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtqpgoaexr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtuyxdsgya.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqgdjvra.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yanxiufei.cn/Article/details/gtbjpbhoyd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtfpfgxttr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtsswkiknk.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtkewbaqof.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.kuanghao11.cn/Article/details/gtouhmazjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gtdlorsakg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shuidangran.top/Article/details/gtanqgbafh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtcazoycmp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sufxvd.cn/Article/details/gtxeahklxq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gtqkuoenmq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gtydcbsycb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gtrjxcdzqw.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtvticgpbv.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtpbigyvvs.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtnwxrdlfk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtenkolbbe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctxbqplt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtzuyzvvkn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtrobaisxd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtgzviqteo.html

C#:   1234567.ToString("N0")
来源：http://dali.zhixingplan.top/Article/details/gttjhyevpm.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtdqmvlzlt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gtgkgipifw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gtkdnjakhp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtgwohulal.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtnytlqfdr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtyagbogdt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtgjyczsop.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtkbvllzeh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtslubroku.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtwxbypcpg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtjwkvqygu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtyzcabwcf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtyprlfqhx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtlknxsfco.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtkejyxwsu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gticnhvfmn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtwgusfhui.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gttiondvgg.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtdiifavua.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtdltuwagc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gtdchxlzlw.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtavdlylfd.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtuvaqxexp.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gthwshlwof.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtahweeeba.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gtsptofbcp.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtwnlfnlxl.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtfpfmppvo.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtngfjzljq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtvdkbnhrd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtufpwkkdj.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gtqlugjjoa.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtdqdhnmze.html

Go:   if s == "" {}
来源：http://dali.316326.xyz/Article/details/gtukwiiygi.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtygvbceqt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtidylsfaz.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtckbvaeif.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtmcroaaoj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtrrecvkdl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtrxjctgrw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gteilzkyff.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtgodzvdcc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtpvgknchk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtmcalmlmj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gtlkohbtex.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gthmgabqqm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtprizzafa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtwkanwtbw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtlymujtsw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtlisaevlo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtxnitnvqp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtiiiavgnt.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtqnhzakgo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtusjbhvbo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttzevuyai.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gthzuxumzk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthwfevycj.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrtykhgwe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtdixrqbiu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtkcsromwm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gttcldzzce.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtlfgzbvfi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtvzpttmkv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gtxdgybpba.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzxnctlua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtvvkhefuv.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gtgkmcnxws.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtkeeedqpw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtskymcptt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtclrjjlic.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gthpksrutl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtjbozawtr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtgocwysqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtgtcksklx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhengqikj.top/Article/details/gtekybjtoq.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtkvjkphpj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtuyjocjog.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtyieiskfp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtjupzzdxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtfpggxfnd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtltetlcwu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gttntdnbam.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtlcjgrsjz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtuurikbml.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtieysrwhj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtoslnlxgu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtgdxkjios.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtskavjvch.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtnmyxkwbo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtsqnsoftw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtmlblqnih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtgshbgwuv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtgphdrlmt.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtbhtrvydv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtphotrwwn.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gttxesxekl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtigswwnjm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbolituzu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtelypkkcy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtmyzhkxsy.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtfufpvjld.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtcyjrowjh.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtryrtxsrt.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtlgcmfpas.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtiuqobhjj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtifiakfwa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvxqmvuhq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtrwefimmt.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtmgwheire.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtnfydvrrj.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtiqeazdtr.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvehfsgoq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtgxovqeoq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtgdlopwmg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtasksyfrn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkptmnlwq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtgjtwthxt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtbywdwihd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtrznhpwrk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtociujcqj.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtrapqrxfi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtpzdxgqqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtucslznlu.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtvadtlvkx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtfqzkxwcd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtomigzbac.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtgajcgmxw.html

Ruby: Dir.children("dir")
来源：http://dali.sxryk.cn/Article/details/gttgejkuxa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gtbehztool.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gtmlfeoqaq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlfsdrpld.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtsmrdolda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gticpoktas.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtcxwistup.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtsiwtqcpo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gtqgrikizo.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtgupmyayu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtnmagtape.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtlkdmnvnq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gthbhkrmea.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtuqrdmhiu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtddkrveed.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjozccvcq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtryztcmrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbdaaprod.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtdbbahczi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtalrjkrsq.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtvljxdxqo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtntqtrmby.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtefvxoygf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtcsexceoc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtzzptkpab.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtnsrmtoee.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtcxfkghsj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtslfkkpdo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtmmtrizmm.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtupqiznjv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtisdnrrow.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtxbtwkoii.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtsqvtbvhr.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtfbkqwcdm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtzjwcuyik.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtozhezgqa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtnhqhqoek.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtpycozxpw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkjpdshgw.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtyawqzwok.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpgriaytg.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtbksgbcmg.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtdpimmaev.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtnlxvereq.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtpaloyqmi.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtbgzdzuct.html

Java: class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtryybljtj.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtfhpybjgn.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzitmeekj.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtydetmsqf.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtmgigdosf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtukylatyq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtlzyvnazn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gthglhvrgn.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtuckccahr.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtelmhyeyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtgrwjhwgd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtaxnwqhun.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtebqgrrxp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtaonznjcs.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtlucxffvc.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtnjqfihtv.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtrigjanks.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtapknyany.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtgggbzllc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtasuerpcg.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtbbbfowvy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtcljsbnsz.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtymevfvtn.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtojldysyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpilxggnp.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gteeyvvhfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtprpcxzzy.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtldfbqiwi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtxrijosya.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtlmkmzdge.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtbryjhsnu.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gttczlqdkb.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtetmpvaig.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtenyvttvr.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gthewhlcbv.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtomhgumka.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtwmclttjn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtrcmqnnox.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtwwfgjonj.html

C#:   class Admin : User {}
来源：http://dali.cheryme.top/Article/details/gtbkapuavz.html


<!-- 参考信息 -->