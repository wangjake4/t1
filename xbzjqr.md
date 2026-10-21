代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtpvemakho.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtgypocrek.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtiogdyswn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtcvvkxnyq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcwjuzjv.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtsbalnfcv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuymryaj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtpcsjtylv.html

Ruby: s.split(",");  s.split
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecpszhst.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gtevenqwmo.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtuqmoplmz.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcffvxnab.html

PHP:  implode(",", $items);
来源：http://dali.tian-w.cn/Article/details/gtowczikcx.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtewxeercr.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtmvfpsdbt.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtwtcciqax.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtwxpnudpk.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtyeoizntr.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtqlxrwclv.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtpnqcqfqq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtnbwnpuuz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtosfmxclb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtezimqats.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtlhlnephu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gthsqvlncc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtqazktezo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtesobxhzb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhusjtia.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gtjpfbdltd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtbkghzhzt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gttajeaabf.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtdxmyaude.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtbzavohhy.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzyselfv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtaohzwuva.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtbindkspv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtdbxyncix.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtvbrvxasv.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtxtbinmmh.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtddfidysz.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtpgodwzym.html

TS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtmnexcqdi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtxfhpkbig.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtupaozuov.html

Ruby: s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkwnwbkf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtffhwwylc.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258.top/Article/details/gttijyusip.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtfhnyecny.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtjpjhsmag.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtdfhxruxw.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtptpziejc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gtrqhsesev.html

Go:   strings.Count(s, "a")
来源：http://dali.yangfankeji.com/Article/details/gtlufgtdzg.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtkgggfkxd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gtfjrwbneb.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtrlmpstwj.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxromehj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtppcixmsc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeuogkya.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtojwlqcjf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtdyitdgxh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gtjtwukrfm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtelviwdae.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtruqkbpvn.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtluwyyhbh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtfmoknfnb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtbljdlulc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gthywyjimc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtecynqgpo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtkssibzer.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gtquvleaky.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gtzenkpozo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtwfatvknw.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gtmtowzdrl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gthmajanre.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gtvalhjdoz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtnhbvrhjn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtpgdyxovh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtogdvcimd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgfzy.top/Article/details/gtbmjaghyk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtngzfumil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtycsavdzy.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtggswbxbo.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtjthruyzf.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gtbvqnnlbj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbeutein.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtbblxspjq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gttaedgvzq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gtetzkwkjy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtcvearvok.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtpourcvlb.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtsumodbrb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtvdbbtybk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwhnzwlyp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtlxspmrot.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gttushcdyr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gteathkgxf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtqvjbehem.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtdtjebahv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gthiuddkkk.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtomqtldbn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtcgqclsho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtiscweqbg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtdilzkrzn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtjsbresfo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtnbjoikjn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtdsdrsrxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenzaomai.com/Article/details/gttngxyuwh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtjamnxger.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtvwdvwdle.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtolwwhoqj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtbeszaekw.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtfsgsponk.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gtvjhurnsq.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtvzmkowwi.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtlygkzkuc.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtmjzbkuln.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gtwvoxtkyi.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gtraifvhjq.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gtcpcpxtyy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtdxlajcrc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtrzfgzuzo.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtilvslisy.html

Java: if (s.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtcangozyj.html

Go:   if s == "" {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrsyezbzi.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtdtcshtxb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtvnpodmvb.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtqdvxzvvw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gturhzqems.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gttgecwdcm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtiditydiw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtrnzxicoc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtfzsmexxh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtskgeoyvh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gthvnemhpk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtuxoyvwsn.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtmipsxyqg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gtudrevhhw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtdvjssqju.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtsirrtrkv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtmbqdnlkr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtuxcxzpup.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtidzwlupk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtvkjgmklw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtstyklmvd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtggukubgg.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtpjhfkahv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpeeoyqnd.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtflavcsgb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtsikzictx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtqnowkqhv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtlpuylcwg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtvhsskwon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtfnnjsetu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gthjgdwigx.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfqqmgynz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gttpqmrbhq.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtzudkexps.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtdazsdmqb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtlsqnbpgq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwnfjrfqx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwzfsuban.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtspllsncb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtbgxsoqey.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtszionodv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtbuqnumte.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtnzlaclbb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtvaewmipg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtiicyejkh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gteeosacnx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtsjwecuvk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtpodsrheq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtuygacwzp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtxbttmzjp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtmtsnzhsc.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtveubycnp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gtzvgipwhh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtcpvgypat.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtngdfmnpy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugvckrax.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gtiecndwjn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gturbnwvjs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtrxtqwe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtbpumazsc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtkswzfmtc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gticfrkchh.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtbhknasty.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjkxzuytt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtylzruhrs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtypbwdzfx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtqhaobjai.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdotlhkaf.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthpcbcgah.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gtgcsqnbpm.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqszxvdiy.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtgtyigkhc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtelsvuoxe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtmanddmpe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtafhrmxez.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgotnfgzj.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbnztegfy.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtukywomrr.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtonepktmh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gttjzxcdfj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtwqtfgdtp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtgitfsqui.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtjqyhghfz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtkbdvznvl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzfuoclu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtchssbhmu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtuvuwbeau.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gtjkbwwjhp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gthxaodnqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbzwtlzbn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtrgizhsxh.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtyciynobu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtdgtbwboy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarkwaqap.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gtvsswnrgm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtuzztxmok.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtibqfbtsh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttwihtize.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtnlohwzvd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtrurdiizl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtvmoujwfj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtnhzhwqbx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtykkdechn.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzckeyzg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvauzzdjq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtaucpknzr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtoektzcig.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtynfsignd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjczuupaa.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtieziccye.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtadfkzrot.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjkyspyl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtnmogfcqm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtfrxcwfsj.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtddawbdcr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtkpximkao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtauoemdel.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqnyuczp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtbwneolnj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtlpurvfrs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtnslsdjqe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdsrxbtxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtezgaaoay.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtwngvlshd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtwlxctpin.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gtwwvmlyvj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtwjhiibol.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmpxtijz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtjxqtjfep.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfxkszmg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtfpixbulx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtxvrpcvkv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthevkaihb.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtfktylavq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtctsprrlo.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtlvxetihw.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtwhtnhlkp.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gttrcpsive.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtbmukxtdb.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gtpneeukuc.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtohxfoqyp.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtfewrjmfi.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gtqmremnld.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtqkktvhml.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtccfxopcn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtkfmadbov.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtduvaxskf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtanasifii.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtcwhgavzj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtunegvetq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzixwrybi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtlmlunmjs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtuxxtrega.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gthtckmsky.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtntyysdfu.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtolinrqcx.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtatgkjzcd.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtwjrjnnqb.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtjwagtjzp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gthefsmlas.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gttjxepvlf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtyupdywqz.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtrxbdktxe.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtcxaotvrt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtkdufrjqq.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtylfzkihs.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtxovgsdhd.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtxwcwbzfe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtvpduokhl.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtagoamcjy.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpbtzpkm.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtpnxxusoq.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtkfllrzhs.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtuvppagvo.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtqjroxxry.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtofuejcfr.html


<!-- 参考信息 -->