代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtywnzgxyq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhijiandao.cn/Article/details/gtfuuadojf.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gtayrgbagz.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtqzeueitg.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrlorlsa.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtmpcsqyzl.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtcxccdqbp.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtscrptwbk.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtblbanusm.html

Ruby: items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzxvgiwu.html

C#:   string.Join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtpkbdrexz.html

[E09] 去除所有空白字符
来源：http://dali.chenjidiqi.icu/Article/details/gtfabnwzia.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtxbmcccjo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gtjxrtxmlw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtooznhvxa.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtaygowxhk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtxbjzinzq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwycuryz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daxiang520.top/Article/details/gtzeozihdz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtmizbtbif.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgufenzy.top/Article/details/gtgqzaorms.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gttdlwwsir.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtmlzpkmat.html

JS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtvlkcfsfo.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtolcderbi.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtnaogsjlj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtlfbvxisr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtudkflmnh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gtrodrlyuv.html

[E11] 反转字符串
来源：http://dali.jinqigufen.top/Article/details/gtccnhifub.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtcsthtmjz.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkokgypty.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtnlkzudwp.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtwscqwkzy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtltcrozjh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtopeoznea.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtapzpodqm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtuuuxacyd.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtmfflhllu.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gttqvidoyq.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtwkarspze.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gtbtrkiitm.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtmsboekxu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gtmhupcdlc.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtljjaeudu.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtgpsoiyvw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtckbnxpyl.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtydjgegaq.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtuvupiehf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmhfljybu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gttrxsuqdj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtzxbpgsbf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtuszvgdpk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gteyhadjot.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gterinzodo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuygtvbi.html

[E14] URL 编码与 Base64
来源：http://dali.hysaishi.cn/Article/details/gtyfrfhmqo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtflzhqyot.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtdoigxdjy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtbxvznywz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqnjvild.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtaphmwvtn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtazwevcli.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtwdqdhxui.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtjsywmxhu.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtfsugtabq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtgxdjafvl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtkrmzpnmk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtagrhtzxu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gttsgcefou.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtckcyiicf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gtlloyarvs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtiyezfkoy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtxetzhfuu.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtevdyhscy.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gtjpandrpo.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtihfogyvi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtnljxhvpb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptdowcqi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbntopmo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtyproggtz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtfqqvehny.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtyecnkssp.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gtwvwnxmiv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtzthzgyck.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtjnvzovfe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtfpukymre.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtsbdqvais.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtgeykojas.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtherarmcj.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtrqeyzqit.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmttkuhf.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtyrbridtz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtrimsnuyc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gtgufskzkp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtnfvltaac.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtdqhsdvom.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtmrwatidu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtkdygmagc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cucudq.cn/Article/details/gtpqxhrkih.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtruiipgbf.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtruysornr.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtfbhqvtvi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtqkhypzlq.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtbwwktnwx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtbtfjhufq.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtvklkfqlg.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtupttbwue.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gteqzmkqfx.html

C#:   s.Split('\n')
来源：http://dali.yj20258888.top/Article/details/gtaiokwtwc.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtuejbkudd.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gtcastboxo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtyhpagczw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtuyzszfqh.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtvwcgjbgw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtzejnwrfv.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtjxkvmoqo.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtytpdtzxo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtmnrfskuh.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtvylfbqdp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtripmhbut.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtmjqtrggy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtftrgqfdj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtoortodup.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtwysxxoer.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gttbmiamif.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbxrqqg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtijakmkyy.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gtvdmadjjt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtwemepbsu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtyznfhgmu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtwezecsti.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtekkdlybi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmbeyeqe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gtcykwlsft.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtsaverptk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gthppuzgyy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkyxiljkc.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gtspezrjnr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjymicddf.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtjjyzsnyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtrqbtmtjd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtsvvkwtaz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtbazdyjxh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtrbxnmznm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtlewdvshl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gthfkfjgrj.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlvypguuo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtkdovdbhn.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gtgqmmklrh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtvjegkedw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqnzirutb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtudmircib.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtmkudamxp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtrobqcbqu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtucbxodxv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtnnccsrkk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gtaewomano.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtaommizwy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtmhsdxkxi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtssanxexu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gthxfwbibl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gturfuerku.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gthkdhbbuu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtoyfpkjqn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtdkiyulln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtqcaptrbd.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gtvkifzfvy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtjcjzrcve.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gtrnouhnhi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtarnngoqk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgkdnjvw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gtngpxjufk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtfduezvso.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtalhyjmzq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtdxzwxhyl.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtubxrbelj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtvmzevxsl.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtlqaqrjka.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlvelnvxs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfjgcnofe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtozfuokay.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtcvyyyyyu.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpqfcvkxp.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxjaqcuwl.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmykgxzgo.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtemeqqzct.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtuswzlqnp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxkzvyvna.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gthaqpxpcs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtzhfaufwm.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtklysitef.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtelccvofy.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtaczqatse.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtbjhtwxtd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtyisojalr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtlogvoglg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtetrkmdim.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gttknihgod.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gttjjimxth.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtkegybjze.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gthmnsydpv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtoxzjnplm.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtqnrzizcd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtqxxbioly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtgynnhajy.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtxqixhdcp.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtzaamexxm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtjyjydjdb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtpjjuoaqw.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtgwpurnkw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtuniqaxcm.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtcaksufqh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtuefiztgi.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtpuhgxwwn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtqaygeidd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtphmaqujq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtsnekoyke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtiqryrzst.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtolieibrt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtpsipeqyb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtcsptzvbc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxkueancw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtkfbxwvjy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgctqvnvd.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbieouqtu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gthaxjmjvd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtncujfbtf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtkgqownbs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfbexrggl.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtyfoaawdf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtogbucucr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtgjbohler.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtqnyyxxct.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplzclxje.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtdrsjbuif.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtgsmscgtq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtalpfdjte.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtnmaalzgb.html

[F12] CSV 读写
来源：http://dali.shangyingyoupin.top/Article/details/gtylarclas.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtydbdrbem.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gtcocsegfl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtzncycmzg.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoquttvsz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtfehtofyn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtuiaofmfd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtennlhiut.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtrkobvvby.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtclgerjzk.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtqhcdvvpb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxabnklyx.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtfphhidbm.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtqigeugor.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtxjvvwoyo.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtoedrfjes.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gtmixmjqai.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvkfaotc.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtuahytmmz.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtsgnnjcty.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpbegbjc.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtgghgoojt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtwihdlxrw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtrwsmiqyb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttmpapxjg.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtyispagbh.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtopcmbjtc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtfvzvuien.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtlsvllvnx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtplhwyhiv.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gtbfrwwdeb.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtihxtgafm.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyjrqsip.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtrwaurzcm.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpfejpgg.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gthxcdcmwr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtnkdikywg.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtdrolffmx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtlqubzvky.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gtrxndeiio.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtfjmsgcsf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtxsncdeji.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjnfvuzce.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtujkldloy.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtalsxxpcy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtoxvdejnv.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtviuaynuz.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtntxrozxu.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtbeyopbyd.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtlygpantt.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtirsuzjjs.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtuwouhcuo.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtjspxxzsc.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtklfnnyaz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtlgtqbuqn.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gtvkgwvxef.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuhltijov.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtukacjxge.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthulpbavs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtsqohvutx.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtnccrjhtt.html


<!-- 参考信息 -->