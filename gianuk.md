代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtpvdrnxxl.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtzewmrspn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gtwbqtvzim.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxoqqmqpe.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtsogdnvxo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gttgkxpuch.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtqagiagvs.html

Py:   ",".join(items)
来源：http://dali.yj20258.top/Article/details/gtwozkmpxv.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaeolzdj.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtnnmccwel.html

TS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtsryvslfr.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtnzgvhtwp.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gttmvemcko.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtadhbxvtu.html

C#:   string.Join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtisavmlvg.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gtgbwhrvsm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gtdxifqkni.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqqlntnn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtfapbflxt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtzvmnhnzy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gthcvzyyqv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gogol.net.cn/Article/details/gtfvybuvak.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gtufjlrnjd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtlvhrzpzu.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtklixiycs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtqgcgubjx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtzsthemvg.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtokxrxfig.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtefhvalqs.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtwglrrrxl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtzylqtqnb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtmamsqdek.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gtiisjrfvp.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtgosttmyf.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtldcqtmmz.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtpcjeokai.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtogqmmomr.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtqsksllsv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtupbiestq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthngetfbl.html

Ruby: s.reverse
来源：http://dali.mhx1999.top/Article/details/gtkrtplyoz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gtriofphhq.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnbwfvjz.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gtrseqiihf.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtkwdhyysr.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtimhsgayk.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gtvlxvvquw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.redwolf501.top/Article/details/gtpejlovjv.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gtflxxvphz.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkduiksn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtdtcmoool.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidxxlycu.html

Py:   for ch in s: print(ch)
来源：http://dali.hongshengwenyu.top/Article/details/gthgrivdwv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtmbguqjep.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtynrwmfto.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gthmzfmatx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtxqrtdihe.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gtvdyppekk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtevfzgbmq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gtzxcfcoil.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtacxxarxh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hywenlv.cn/Article/details/gtznxzxzzz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sufxvd.cn/Article/details/gtojtgrnml.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtufpmgtxf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtccuqpprj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gtsvwmnvnr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtuxbatekr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.birdmap.top/Article/details/gtseurqgbd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtyedcmzli.html

[E15] HTML 转义 / 反转义
来源：http://dali.vqdsnc.cn/Article/details/gtgeilahvb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgiocrbef.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtbdyeanvu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtiqheuguf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwykeyor.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtcbcqbhwe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gttxlajveq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtwmroawre.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj20258888.top/Article/details/gtasjmnwjo.html

[E16] 数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtwzjkubwt.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtcmmhwfiy.html

PHP:  number_format(1234567);
来源：http://dali.c1oappe.top/Article/details/gtocqhbrhy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gttsvvdbox.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtayreyepk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtjbyllrxm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgnjgnlt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtrmvjyhlq.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gtkfwdxuqx.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtthuviaei.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtabvakjxa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gtdtqcatti.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gttxsowqyh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cdnleiting.top/Article/details/gtytdmpzko.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhixingplan.top/Article/details/gtycuyhidr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtaypvvcyg.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtdkwqmjwq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gtonrhawab.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gtvooxlfps.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtxecqfeqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtmekslfrv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtevedexxf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtqfzmgpqi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtwqnpkonj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtsdenekpp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gtgcbexlgr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtbeubjese.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtpttmgfny.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtfdgvqybi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gtusmlypla.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtoolbnrsr.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtjytzlhcj.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gtcuryjntj.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtdbnoqzjz.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtsgrsxpwj.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtjzetkjjo.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtkfowphar.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtyqigpppx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtftzbidyn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfbuoiksh.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gthxhecfmw.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtnwmjcamq.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtkkszfhem.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtfqucgdnu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtghrxudlc.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gtfrujwogn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gtahidjwcg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtriuvdqod.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gthhrcgdki.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtgnwmnffu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtrhcgaixw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtatbdneuw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtexkhsiug.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtnsqwzqtf.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtyjhjjnpe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdimsbdyg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyfwlsas.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtayksancd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtpggzlevz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtzsvtuuxm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxlmtqjf.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtrseasolc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gtbnkajknb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtosbbuyvj.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gtusbbxfer.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgtwzmlrx.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gtyofycvlo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gtwpotcwew.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtogqaoadm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtvegymndt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtcsmhoocs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtxjborbny.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtvoltrntq.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgykvdshv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtoiiqhkeh.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtspmgsvqx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbixqdjyb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtgsyffjzi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlpewfdxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtuwlaybab.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtltbhldhu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gthkxsazha.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gtfyqpocit.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtinkkyrhl.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtxnvhedhf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtbfgtsblm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtngcjjrty.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtqiqjhsxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyoudwjk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtkzsisnug.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gtjyhnpvad.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtdepdqpyf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakqdcuqm.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtpvhxzhah.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gttrgdjdaf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtadttndmy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtzbgfksnx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtvltrazlr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtnuktycyy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtixjwkida.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtwrjqvbyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtprundykj.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gthlzyoavi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gtazfqbrky.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtkwwxxklf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthjlcdlhi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gthevttdsk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtluplxqks.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtrchjkegv.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtsijaizqz.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtdiqvtiqg.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjbhtfrk.html

Py:   os.remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthznqmshz.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtkiacrwmi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqwfzyikz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gthyttgocz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtxrnzxjtb.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvxduuvm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtrafahyda.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtiympgwim.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtqmytmqae.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtuaoyfpqs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtqpddxioj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtmlauosaz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtetzaxtfp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gtdxnquxur.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtjeivbwwj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtgtzrfenb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtnaqnumfj.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gtbpptfuqa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtutkgccda.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtgrciiist.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtlstikahw.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtqgdckwnj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtjvgdhvpr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtpqukjphe.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtjcsxoboo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtxrtbfeav.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gttmpyqsdv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtugtpyjva.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtcmvqcjuj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtphswdfle.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtfiqznsnk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtdngickqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtojnaujbw.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnbysypyq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiebjjuf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtfscwsaga.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtewzmmqhm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtbdxrhexi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvrwvwtlf.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfpdrtlhf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtuprmboko.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gteukamudg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsrgiiurg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtbceqafkq.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gtjacfcruy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtqnytqwqt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtsabbquce.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtlsnvzher.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gthetzcnlv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtpcvtfvkw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtuatpkvhq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtcnkkcepo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtnuurwexo.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtzxvoejee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnjgqmpj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtcwfaujsz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtusdmmhxl.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtndjoelra.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shangyingyoupin.top/Article/details/gtqnonacih.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtgigihcwr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtjwawvujv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtejcsoihf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmztbppjx.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtkwsyggps.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmvrrdymb.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtnbizstkn.html

Py:   class User: pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtursjbvcx.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtixsmntvo.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqqkwgaf.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtnavnuogd.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtgroylclg.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtrcjsfmyz.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gthzvdpggh.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtwajmprle.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gttcehpbcw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gtvkhcnysr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtxgkabwge.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtirlmnxhz.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzteiyuxa.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtazlxfimc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtyaplhqhh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gthznbeyle.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtbzmhkbey.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtdbmmxqif.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtvxtlcugi.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagbslpgv.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtfmbymmsw.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtiuoobdhq.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtcooflpvr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtvwolztyj.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtfccemgfl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtenoaqpxn.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtrhyajdfr.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnwlqnjd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtuislqrro.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtsaokqttp.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmjuuhzt.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtpkmbcjsx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtadrlbiit.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtdggeqmwz.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtgjzzftei.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtmbvgufkm.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtrhvtcprh.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtnarjcjmf.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtmtieqpbg.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtfsfvqbnv.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtzwgpdxvb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gtfgdcdsji.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtapwdixpo.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtwecjudkd.html


<!-- 参考信息 -->