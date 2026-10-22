代发 wailian999

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gtsqsxashi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtgfizroih.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtsbnmgzwj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gttpsittxk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtsofrzxfr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtuqopcqus.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gtehtxvbda.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtwddozihm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gthgmnpouq.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtbqfvazbb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gtzlxrfzcb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gtdrsadgit.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtfhvkimsi.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtndjijwpc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtifrgqngo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtajzxjjuc.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtiinygpqa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gtgfyskpkg.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtlznegbam.html

Py:   ",".join(items)
来源：http://dali.gzhubu.top/Article/details/gtfwjidsoq.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gthfviplyd.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtqvpskwrw.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtyqqndikn.html

Java: String.join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtollrosrg.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gtxanplupd.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtxrwviepj.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtsamvhtpb.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtkvsjflys.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gttpmmemzy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtcaijacvc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtjewicqxz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtfzhygdfv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtxkdrtdfh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gtgfvaygaw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtulkmnjqq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtlzdhxenq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtwlosvter.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtdkmgxsnx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtsxqimycc.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtvejipegr.html

TS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtulzyghgn.html

Java: String.format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtrqzojfkh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtarqyevmm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtmlpdsbmi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gtxaevgdex.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcutgunl.html

Py:   s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gtvkvaazzv.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtjytounlc.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gttzfwcwxk.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtanzpqijp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.mhx1999.top/Article/details/gtubbzmmrf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtzpoalded.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtecmqahll.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtwkzlujcx.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gtbsidubfm.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtagwwpwss.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtffyseyab.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtbpmltrey.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtfluhvmik.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtidtzeizy.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gtmricmjve.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtnmotsyif.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtpjggpqor.html

[E13] 逐字符遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvohnyhvp.html

Py:   for ch in s: print(ch)
来源：http://dali.pycfn.com/Article/details/gthadekeys.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmmxrngfs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxkvltrk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtyosuxlij.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvooztduw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtgaqsmifk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtlxqjorzn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtgbvbcivf.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtedlxsoqe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gtcxicpinm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gthgzadaek.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtiobhekxd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtsvpwtdhu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtugwuzvqg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvtxxadi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gttxjtpbmc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gticpxwgnd.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gthzpndueg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtgzyephbz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.bjfxy.top/Article/details/gttaujsouk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtireqritq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtrqkdaraw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtzddlwlcv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtkjunneoj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtlidlqzra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtpcxvdsxq.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtsafcumvv.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtgndleguf.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gtijxahvut.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtgacjgnnp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtmqudnzxo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtjpgxzmzt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtxslwtaka.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gtstftrggx.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcukshhjx.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtyxcfxrjq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gteoejxotv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbofspatj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtkxbyaptu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtiebwfiis.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gtkkqticat.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtmkzumqal.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gtvkuqtyay.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtemefmwlk.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtvawrswaf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gttnxizamu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsancylp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtajojngpe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtngoxeckn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtpoakedbe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258.top/Article/details/gtqhllhzej.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtecljywda.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtsgqivwsg.html

[E19] 多行文本按行拆分
来源：http://dali.iojbl.cn/Article/details/gttejquoeq.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gtajnjists.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtygephoqd.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtphcxmrbv.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtpwpzrtrv.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtznmlbqhh.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gtqpeqqssm.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtiflrrmge.html

C#:   s.Split('\n')
来源：http://dali.shzxlz.cn/Article/details/gtsqyvegtr.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtajzbzfuy.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtnfblfidt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gtuuqhgawc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtmzjtqlaj.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtuicgshcp.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtvsoudenh.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsbjvcfzw.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtfhvupyhk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gthhibjhpr.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtcrpurgtb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtdywqutbn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtyhsbboue.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtwxfwdmcz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtemfebswi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gthsvbomuy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gtbpusoknc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gthqoagmlc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtuwambqci.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtperpqpus.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtdcdzcexb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtonzgjtly.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzamtzrj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtslvabsft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtpfjzndqn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtkhpvfubd.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtbvwaodfs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtuqkjcdyz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjmehytch.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtyrrejnvq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtitsaqggs.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gttlkdngqm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtgdfzybvw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtuuiusmfk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gtlataobxi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtemcbbdnd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtnbmwpadf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gtcxtugskr.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtxhnuftxh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtzgvrfonq.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtkqbgxbnu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtfoaflytu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtoxmpilgl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtmocftkwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtwgbrqkin.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtktxdtyig.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daxiang520.top/Article/details/gtymjlkghk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtshwhcwqw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gtzkygbjqq.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gteucmedib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtlovdgeqk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gthkaqwhpw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtsfajfivm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtovxzfziu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtuoaeegwm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtgrifzedo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtrdrulptl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtozklquaj.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtvkerblfv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtqrbicvss.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtnmybdega.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtporpaczz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtkusenmev.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtpnhwehrb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtrhtihkoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtrzwdrrea.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtarulveix.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtsfdfsarv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtyxvhqlap.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtmibspgxe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnrdktwlb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnbyqrvcp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtkostlgeq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwfqxhyq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqspesdbs.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttbtfljml.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtczvdlhdi.html

Py:   os.remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtpcoxmzqn.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtofryzfbv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtykqhgnsp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzvxkeymb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtwjerbgka.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpckpqmyh.html

Ruby: File.delete("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzhjwubrs.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtxzzvwygr.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtrdjmkjsa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gteqfmaltt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtmuqjkrfx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtoezxdtzd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtbihdvcuj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtstlhqrft.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gteweiilka.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtgwmabwpu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtmiciqcqe.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtsmtlmsns.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuewxxvc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtwmdblrmp.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gteuqmuggi.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtlsprqprh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtlmhkhtfs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtfglczydj.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtltbnvhli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gtluesunoy.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuodmven.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgqqknva.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtxlbpudie.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtrnibhoui.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtvyzarfln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmikanqes.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtejxwvbch.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxbrfmisg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtzawdmfyk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gtvwgyzuvu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpfldajcr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkfcwjwx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbnuyualm.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtqecdlbqj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtncftkfqc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrlzlcyhi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvrazpbhy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtssvpsoab.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtrhkvqved.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzoebvizl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtgpuilkqm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtfosemnfo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtauesclen.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzbmvfeo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtabhkohwx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtizyyyoqy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gtwcszislj.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtsvqpxyhn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbfsnpsk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtmhlcatob.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtldqexows.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtbrvjahnr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gteynfddrp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtxtugrjwz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtbtwtallq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtplyenkmr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdkknlnd.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtxfgwxkoj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmddwxnvh.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtjlvkgrta.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gteygzlwnl.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtxvsnavpr.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtfylfwfyc.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtjpxdyltf.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gturkcmkbc.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtwrhpksnq.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtmhizsrxw.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtlpxdhxlz.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtakssnjpl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtjaehuxsv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmkdados.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtcaymlgxn.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtfykjprkz.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtnegzprxh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zdqjudy.top/Article/details/gtaizqixnx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtnzuincvw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gteepxhaat.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gtgaovwcel.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtkyboqaxc.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtpwjfrgoi.html

JS:   this.name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtuyzaavxf.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtgxlljdzw.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtihxgrxcp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtwzffitvr.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gtakxnmggl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllqctaia.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtvhecrjft.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtqemsymmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtqhcaxqvo.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtrcbdlthx.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtzqbqyijf.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtckdmmzyc.html


<!-- 参考信息 -->