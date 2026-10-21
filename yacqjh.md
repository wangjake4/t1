代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtdciisasc.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gtqwigqduu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtmdebvzsk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtgknnqocb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtaatblfvv.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujxbyyzs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtdjlujaog.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnxiangtu.top/Article/details/gtphjkrstr.html

Ruby: s.split(",");  s.split
来源：http://dali.xziqi.cn/Article/details/gtdjanpecf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gtutftssdv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtwlujjrrw.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtycherewx.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtkimnpvzh.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtwttacdgq.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gthumqwyed.html

Java: String.join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtdnzcatth.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtfddlxywo.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtzbnnbxgq.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtabnfszrv.html

[E09] 去除所有空白字符
来源：http://dali.zhoulong.xyz/Article/details/gthyjsiuor.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gtiytmtlhx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtpgsbexhj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtzzsfrloe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtglabgnbn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtxxqhzcsm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gtjbtjywle.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtprlhbkpr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtrgzpeveg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gteeuhgjps.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gteigtmwiq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtymmtggjd.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtgixamkzs.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtfvnpqtda.html

Java: String.format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtndjkqbgo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtinnasfnr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtonhtlamq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigufen.top/Article/details/gtqiqgtjnu.html

[E11] 反转字符串
来源：http://dali.haohaochexian.top/Article/details/gtxyrmyocs.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gthhshsvhr.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gtkczycnhg.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtdfnuuctp.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtkpxzvkhy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gogol.net.cn/Article/details/gtamrmyfiz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gttkciblwk.html

Ruby: s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtynmrcauv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtvrsunhbx.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gtwqqrepdw.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtvwethoqk.html

PHP:  substr_count($s, "a");
来源：http://dali.xylfe.cn/Article/details/gtcjtqmpuc.html

JS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtazpvillp.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtnlbmxfwb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtyilzzrsg.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtovsejpjp.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtxhmgrdxn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtzjjofzpd.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtgwoegrco.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gtqfxuioof.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtfvfskdlf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtwhrhltql.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtsxkkrrea.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtlcvlmwcf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtswaudjfs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnqzz.top/Article/details/gtecnzfrxb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtrpvxkxod.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtlozgnnax.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gtnvhxpsdi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtaxkwmtzr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtutbsiwhh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveiamgvz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtahfbyhak.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdaplmzl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtvlcqqvcz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtrutxncfi.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gtopsxalcf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtngdcsudo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gteqhmdhrh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtwpzcaqzn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtmcfwkyft.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtvtahznpq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtdopqgyyg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtqnvtoojv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtxeipplmk.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gtcvyxsazj.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtvwlrxdpx.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtaejbmfbc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtjvffjekt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gtnnbhzhsa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtptdyseba.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtlwqtesuc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtbcximjsb.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gtnpmhnmiy.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gtojlsfhrr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtzskhimsd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtvbgxzphr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoesxjqtq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtgsdnidcs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzsruldxk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaunykob.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtylnofwnh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyxnzlah.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtaezxiuzg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtnvzllrjk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtehvqvqwp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttejfdyew.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtbsrnnjbi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtdnywwqqj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtjbxlclyn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtzmigehse.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yonumen.top/Article/details/gtlebppvqn.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gtqujwswma.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtrrpxdewq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtpajyqydg.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtuofbfbck.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtqkvdmemf.html

Java: s.lines().toList()
来源：http://dali.chenzaomai.com/Article/details/gtrpsafret.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtmzwyhhdk.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtwayquteh.html

C#:   s.Split('\n')
来源：http://dali.c1oappe.top/Article/details/gtpsenpwuz.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gtubjxleoc.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtvxezjgoa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtfcyezahl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtxvrehsvn.html

TS:   if (s === "") {}
来源：http://dali.sweek.top/Article/details/gtbaqofowq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtozzfxouz.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtiwosfkdj.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdyypwtk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyipwpolo.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtdcufyxhk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gtxchjhtjz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtymctvkqi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtyjzrhozj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtfdbhsnjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtthweuziy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gteulqqaig.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtflxpsbdy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtewteyape.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtuvyljqtb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtngjuqpbo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtfkmvqwbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtarvadypw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtnsweoovj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtcwmanrln.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtuhvazjku.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtggrcsxwk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtsdvtdnpp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfgjevsem.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtudwfjgwq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjphhpqnp.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gteloicngx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtdlohatmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtwzmaioly.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtuizkcqnc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtqozyuqnx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtlsccqgmj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gthiszplwt.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbzhrgwej.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtlsrhusyn.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gtlooqaizm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtknnimvjr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gthljkthqx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtdggluttl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpezjuyp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtztcfdlit.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtzhssopzu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtfqrwjxeb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtnpfiiadl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtlydfcsfl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gttnxzwokj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtjixluebq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtuihymvsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gthvobxxlr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtupdiggee.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwioudjt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtomvhbaud.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtnwiusxnx.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnlqehmo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtjfvkjtsx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtcaauelkc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtupofvqut.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtubkzfgmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtxbhhndeb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtxakasxnv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gtsmofefop.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtlawzyvsx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtcqwpotmw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtfifwmzdt.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtksqhuxuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfavwukjd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtktboyssy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtbhlpyjrb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gtwjxjesqt.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzpsqgrxl.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtibwmcghb.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtucrpcdfd.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzdmytnyk.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtclsdrbhe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtspswbxtb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwslwovim.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthxncgrvx.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkybgrpur.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthptxswvr.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtwdejdvkh.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gthimlqxzs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtugnzxqfl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtpgabemjk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtrqpmaznu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtbgyadncn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtdmcquyoq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtlluzhbve.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtybmtgrtu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gtkklltvgi.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtpzondgsw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtekwadvyc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgjqpoaxb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtdzydmmeo.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtuszeevfy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtasouxoln.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtixvzzjsf.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtbexkrhnz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoenunocz.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtqyxpdxcg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cheryme.top/Article/details/gtevmurscm.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvgxmicc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtqykassox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtnjagtdmf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnezsahzd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtoiqfrwdx.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbbavrhuc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtdpzdmqql.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtwctmmlzx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuqiwgon.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtcwmsleka.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwuazgwqy.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpdwuglzp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtcafbdskm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtcfcrvduv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdqfrclvd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtrzdewjdb.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtkktwvslq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmoueqieg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtzilemnyo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gttbvhkynh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuksdrbyz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtjwxagfwh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtoxmnvscf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtqglionum.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtsavswytk.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtszxlvboj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gtvpcvvqmw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtmyvcculg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtybriyjgi.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtrinjbcji.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtyjebwncl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtjxsnqhts.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gtomhdlncs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gtfqtqzzsj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyrmauowe.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtwlbsxpoy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtoczkxlfp.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtjdfznpuz.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtlweicxhb.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsuqprmsa.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtzijwzveq.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtwwwwvbot.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtlpzpkvdc.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtzjjmvhvt.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gttygtaxtc.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtrnvvabhv.html

[G02] 构造函数
来源：http://dali.hywenlv.cn/Article/details/gtrrgekrnj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtkcutqohp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gthohoynnq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtcsraghel.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtyewaztld.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtwvdjlhlr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpseszjgh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gthwduurbo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtgehxnkxs.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtwyyuyomq.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtryvyhizz.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtujegmwmj.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtjvagsuml.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtqargruei.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtzkcqjnbx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtiprymezp.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gticsmdwxa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtufzuakhy.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gttowbfhyo.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtagfbqcfs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtyplwzhcn.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtcpcaishw.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtlirthdtd.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtfqkjfnbf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtddngeuht.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtrehylsxe.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtsnpfaadt.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtgevgvgha.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtpxrxivvq.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtujcdabec.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkvkgjzna.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtydginbbg.html


<!-- 参考信息 -->