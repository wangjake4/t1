代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtsfrarxfh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtectepjbt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtwumwwmfh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtitxvcoqv.html

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gtpdzeglov.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtjhlhgibw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtnifbntnz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtehgjlmkl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtmyqkzfpg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtshurcoxu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtpelrmmqn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtyqnsxijh.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtruoeqcht.html

[E07] 按分隔符拆分
来源：http://dali.tian-w.cn/Article/details/gtdtqgbsmp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtzvoieihw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtujynjfvt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pengpengdd.cyou/Article/details/gtmwfqjrbl.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gtieemeccl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtgblvcryc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gtjvlkcfto.html

Ruby: s.split(",");  s.split
来源：http://dali.zdqjudy.top/Article/details/gtylosdyaf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yonumen.top/Article/details/gtfozmnjto.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gtqysqhzic.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtqaqovfsq.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtdotspugu.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtfjnebgzn.html

TS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtwqykphcw.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtbbvpzkfc.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtwlslzhhr.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtegrjsdta.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtwiosoerm.html

[E09] 去除所有空白字符
来源：http://dali.aizwys.cn/Article/details/gtxjsstqql.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbnjonuu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nwbrower.top/Article/details/gtytgcktqf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtexedmzcb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtbefvursb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gtrnvivoii.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuanzhike.top/Article/details/gtxvibzwhu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtqdvwebld.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtcpjwrekf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gteshawzzr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gtmxeeeuiq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtliifrxma.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtgaspmlpt.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtqagmuulm.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtnjcwnvdr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtlcpvrbrr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtjzgsoyuw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gtgldccfll.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtvvzqaoes.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtlltijajr.html

PHP:  strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtjccoqwws.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjoimdyz.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtrvwniwpx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtbgiofxfm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jianghu66.top/Article/details/gtecsbcisn.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtkpapllev.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtflunfxnb.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gtvbenownd.html

Py:   s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtlrqrumec.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtemssardk.html

JS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gteghgikja.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtydlkkapc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj202588.top/Article/details/gtkndhbpox.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gtnqwbhnvg.html

Ruby: s.count("a")
来源：http://dali.iojbl.cn/Article/details/gtjvcbeboz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtvbpvkftx.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtkevlkvmt.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtswaiarfl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtdwvokpyg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtmnmztyoi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtipbwhcbr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jianghu66.top/Article/details/gtdxrjbtte.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtooqqzzeg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchkkwnvp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gttgphcugd.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtuvrqip.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtcebjpdja.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtrnlclsug.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtivolzvxb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhoulong.xyz/Article/details/gtlcgxhcnj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtfpvvfzbe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtjthrrosn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtowtfhsgx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtjjnwgsux.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtriqktpus.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkfzprdt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gtojwqfrli.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gtyniqyixq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtuhnpfmtk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gtfcviozlj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmjcsvkp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtjyvmmezy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtrdreczeh.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtiaboqhyb.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtvmttydhe.html

PHP:  number_format(1234567);
来源：http://dali.zhongyouzk.top/Article/details/gtbadxmhjt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtntdkgenv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtgjursjtj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtnwxaplfs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gtnubykcin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtnqmcvrow.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtoxulpdbl.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gtvjcheaor.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtiyxtoxyf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtcipzsruk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtmfjffgus.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtgdxncwbw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtgumvefnp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtuvzwonxw.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtjmpdhfxg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtyfjfolqs.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtxntggqwb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtmlocvxmd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtmjnplcsv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtfhdume.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtvvibgovj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtimoasasg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtamyteltd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtwyqlcgqp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtxiwbfhfm.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtuizkhgyl.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtpupbfavz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtxehgtmiu.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtrzggemuv.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzpdagkv.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gtjjgdtiwx.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gthogjzsfk.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtgejflmqa.html

C#:   s.Split('\n')
来源：http://dali.yueranfly.top/Article/details/gtdeaoepgt.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtwbqwyjjn.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gttzopgvam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfmivmor.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtcjgpxqss.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtnfonrdxi.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtgqnzmqyv.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtkmmhgzqq.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gteeiswtio.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtctzruhip.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtjcicrqfa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtzrelpppv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtgnvmputn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtnidxqfen.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gthsfvpyqx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtjelzjfrh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtruwegaei.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtrqwipilh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtppnriyju.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtxfogxpel.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtthigzyhe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtlrgwixgo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtyqauzcst.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtdkzdjyop.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtatnzkvmk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtxfixtwin.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gttrinkula.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtkerkkkra.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsimdftuh.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtwdjwjece.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvrynspnb.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzsyxdhxq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gticaytlej.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtxoiogadt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gtcclxdwyx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtockpkdwt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gteauzbaty.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gtcmcubqwm.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtjpuiypor.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtezsrnrnp.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gthejcsxuk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gtjqozwxqx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtahmvuodp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtlkaelqme.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtbyuaevqu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdanlenqk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtzfgsroqx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gtzpjtqcfy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnyykxlci.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gtsttfynaf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gthnvrlgko.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtygnwvasd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gttnelvdgh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gteqihnojr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtcoiojoev.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtrteitajv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtteuffinj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtitxiwuqe.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gtfhdncafz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtnqsyrest.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtuesaqcvh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxeakbvw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtfiysbqyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gtaugdloxf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtkvwzpepa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtnlzagqcx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtxhhyikbc.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtmkbgpnfb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtvajxsuus.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtguamnyww.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdbsgoiic.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqyrelyop.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gthrjkwwvf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gthjlynpkd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwisznddf.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtubegdkqp.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtdwhyqjqx.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjdzntryq.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtrkmcxjcy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbtwxprf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcbztoyfs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtqrvkzltr.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqnuopjpe.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtjkamblpa.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtoaeozpcw.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtgtxcuzqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtpthxgdlr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtzxwiptjm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gttekhddtj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gthagcspfu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtvpqaejel.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtpwhtbtth.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtswhhbseu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtdrdehjrw.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtxjbzalsm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtrajvbltw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvrmitnd.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtunuzifyy.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtbknzjnni.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtrappdday.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtdzofzszj.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsvrmhgia.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtnlcvfsnw.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtdgotsflc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcjhgpnuf.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttznwrhtq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtlawwizsd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtlckstlzn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtsyixqxax.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gticyjmyve.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtracrungd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtzlkykvxd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gthnmtgnmy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgxpvwjey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtixiposqj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtrtgockrp.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlhgzynzo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtbavtxgqb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtpgawhisw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdshrruzt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtqnnwxmil.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtqugpvmjm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gthjnnbgyt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgvsrzvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpuaekqzm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtvwsmusif.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtiojjekbs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtybokvkej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtcxwjshmq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtjnayvoru.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtgzdgonuj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtyakexgwn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtuettkefb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtmrrdrehl.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtigkqyumu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtjqtoyltj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtzxxpybyn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtuxihicgo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtyuwlgxhc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfizgqsri.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gttycfgzkz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzfcbtvde.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtsvtnbuig.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtgoltjugu.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtvqpbbmhk.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtkczbowto.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtuyzrnibd.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtgzskchjh.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtpnuouidn.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtzvlbrjvq.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdtifnld.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtcsfvfahi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtolhurzok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttsbjvnxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtinbhmwtz.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtprsigfmb.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtjokroaqn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtubmochaz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtxozaaheb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlvsioalo.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtnrsvuouk.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtcuajnwxm.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtmatonfpt.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtclmdgrrw.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtsblklbtm.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtxfdsjsxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtjbtkwrzm.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtlioisbmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtirsycikp.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtwpnkloem.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtjcxcivsj.html


<!-- 参考信息 -->