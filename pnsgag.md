代发 wailian999

[E06] 替换子串
来源：http://dali.hongshengwenyu.top/Article/details/gtkpzjsjts.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtvfmlibkn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkbldcqxy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtgsfepkvn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtlaoitpdn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtgsxdueow.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtrubopgik.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gtdgawaeaj.html

C#:   s.Replace("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtnnlfywkp.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtzqdxnnvc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtcwlopjhw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrnsytwgx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtjiiwirqf.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtkpnpclhi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gtbzpvfake.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtmgmiogij.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtwhwuekoy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavuppzmt.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtkkxjihej.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtqppxssaw.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtookecwjl.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtyvssvkek.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gtceksohxi.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtgahcgbdf.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtbujtnbqr.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtisowzgzd.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gtiiwokyus.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtoxshxmeo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gtogefybmj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtmnwiszcy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtvduspoyw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtcjqeeqql.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtmurhwfcd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gtkvftszdj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtptcdsdas.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtvlzuxrqh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtwwqgvwxm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtdkckfdau.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gtdrsanfuj.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtjakbemfc.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtxcaihgyl.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gtwnzaasns.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwbkoozj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtbjqfxwcw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gtufafatgw.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gtcudhzqpt.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtzfhwndjc.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtbjixecid.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtgfgxutng.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtodmyrhyf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtlmkrmbzp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtaqhdyqsp.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtrrvkpean.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtkrrdghgs.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtptgwypux.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtbrxpnnil.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtyzfrzpbf.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtybxzwmye.html

TS:   s.split("a").length - 1
来源：http://dali.hfpthk.cn/Article/details/gtcmncxznl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtfwfhovbb.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtivbfqmjg.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtgisremwx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtiqidtszq.html

[E13] 逐字符遍历
来源：http://dali.smart0.xyz/Article/details/gtvxytcikl.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gtxzrqjhdu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtqnklzrku.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlkcdfgf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtqtzovyof.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtpaqnqqhi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gtcziruqsb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtszradefs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gthkpjjdbp.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtyocqoypk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtyvmhbosl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtvvymyglx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtoxcyvmar.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gtkumgxcqb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtwerawafq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtozervfqq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gthvuexoyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtcojpvzuo.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtuihsxgix.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtfecrwvau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigufen.top/Article/details/gtycbrvuet.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gtvjlclkxe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtzmlptxbc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj202588.top/Article/details/gtheoglkmw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtlmydxshn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmouauvab.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gtguossvec.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gttlwajjfy.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gteqwclvvl.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gtclfaqnmb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtfqkzvjry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aibaodan.cn/Article/details/gtfifmuimn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtvgiowdhf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gtufdituep.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtrcozcpwm.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtltzvamin.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gtfgvnuamq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtymqkwryx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgcooxat.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtqwpyczgj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtjhvygcrp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gtckscsceu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtxtsnsbea.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtekjbcklt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtzvrthfpn.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtqzpzwfoe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtrvacwzxl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtwljxuuac.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtgcojhrwp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtjzavrozd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtbesjjyuj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtwlybmjym.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtjwnfwnuq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtslgohcqk.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtcuwtlpoj.html

Py:   s.splitlines()
来源：http://dali.hongshengwenyu.top/Article/details/gtlhzdgxgn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtfqdikrmq.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtiumbkyxp.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gtukcyqeig.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtzizudnfk.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtaiutajps.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtkdhwkzug.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtliehgzki.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtjkxhidgo.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtygseopsr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sweek.top/Article/details/gtrvyuyayv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcpccjrsj.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtijcrjmfw.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtazekqfbh.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtisehbrnl.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtqyqhbsbg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtgnpuvwwv.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtwvwtbwtk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhlnozga.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtehciajqs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtgcvwzrdd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtsfzeejix.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtsmlkknnf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gtlrwilypn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtbpfqdika.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtlbzpxado.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprrltrtx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gteeidthfq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtbkcisncl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkjxcwko.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaofijxw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtjjyqvuxg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtjfnzqbcv.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtldbvbgrk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtamysjiiq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtscwzfyen.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgonnhmpg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpcgvjhqk.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtrwhtmlkm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtsczeamyg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gtpianedok.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gtgtvfufbi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gthxiifbqc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtyjiuycov.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gttoxqipai.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtavchuosy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtgpvkqvzy.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtwksfqixj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtbwgmeokv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtdxtquvrr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtoyghicdn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtyruolfnr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtcbvptizc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtajapnxcs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtclenytfe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtlktwmoyv.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtyvmihdfe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtflnengnw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtmupwbcaz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtwmfojdsk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtgsskynwu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtbtmpdfup.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdnjubzv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtadizfiwf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtkryckmfr.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtpifofdxd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtpfqfivyt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtvdvuaaim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtvnuqqied.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtpnlkcvjt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtdvxmsqqj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtifthzqob.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtftaamivh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtdowhjocg.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtwaktmkvt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtaqwodgyw.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtpugptetm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxazcrojn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtczeqapnj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtlnqwcuii.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtahbstepl.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtpqpcwney.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtouxesoru.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gthmyhcvwz.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxlilcjjj.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtldbwraqg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjfbzpfgr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqqunvnvt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtjegljcqo.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttqlqykba.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gteggcobrt.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnrdndhqn.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gtbbrltdvm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtkrceuabs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gtcoryimkg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gthnfstinx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtaxakydsv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtzztrqtjn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtciiwujxg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtjqepbiyw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtgitgytze.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtwianjxxx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtxdqowkzf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gtjcdlbejc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxmvbjug.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtvsehcxvz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtoynzxage.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsieernhj.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtvriiijbn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtpnnxupks.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtetgnkvxv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtolmacksb.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtncwbsbfa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtsluxpaef.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtmcwnfrnn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtymxoajjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtngymfols.html

Ruby: File.size("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtsiojdtkp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gthehapbbo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtnqtlyzka.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gttlajbjaj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgneboaqa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtaoqizkct.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtoecunzqf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtnzywlipx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtiyxbcmdf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttaftyyks.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gthakczrwx.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtpyvxnsxo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmahrgbq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gthctebgjk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtujqjjtql.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnubkctet.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtguntkhdb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtyiemywrw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtdlmvjkcp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtvsmzicly.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtooommvoq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtubryqhkf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtkrhvbmlw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gticjcaxeh.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gtigsfnrye.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtnpznssjl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gtvdntzxay.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gtkysnnagk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtphgssunf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxpxbuqgp.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gtissrifch.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtrzmireqt.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gthmzdypfx.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiawnvhq.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gttarfcyyv.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtmlwmress.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtqaocbyjt.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtltqaydcg.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtwtyughij.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtjkmjmecg.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtkkkniiya.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtzlncorzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtgnzbduoj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtdjacklwc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gthdflabgt.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtozkwgnxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtwhxsqhwq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gteemnbbzp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtfurkuasi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtvjkddrvh.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmoonhdm.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtqxzulflo.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtppefajpz.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtxwclhhmb.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtbvclxobd.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtdroopezg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtwlbryyak.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtisctdbtb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtuqenkfkf.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gthotjziar.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtdatazyrj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtxukrbrez.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtdxtixcfp.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtdnppwwew.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtdnivbrbh.html


<!-- 参考信息 -->