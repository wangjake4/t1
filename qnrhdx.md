代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snysgqqd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gt2gqrlxism.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2jliozpwq.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gt2agpsibcn.html

PHP:  implode(",", $items);
来源：http://dali.nwbrower.top/Article/details/gt2zuvoctud.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2inpsqxnv.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2kvzucgsi.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2rgavrqdf.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gt2ydmplvoq.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gt2shgwnhla.html

C#:   string.Join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2hhrqribj.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gt2argymxfm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2yojqjgdn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2xjatvjqz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2vbdqhldv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gt2ijxzbfpo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2mxprxbiw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gt2evnovmec.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddodszek.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2citvfhjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.smart0.xyz/Article/details/gt2mezgpqfp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2kcotwdwe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2aobanool.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2cywieqdh.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2urpppubt.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2pplrzqqo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2fmntekhu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2evznijku.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2isonzzfl.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2lzywnorw.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2dazowuoc.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2msqyyvir.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuojeiit.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2jshuhmlj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gt2secbocid.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ivvv.top/Article/details/gt2cvvmdmbq.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gt2cuemimvq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2tfwcjxjv.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gt2iurcyfyz.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2qbzaikpf.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2ivdjjifp.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gt2dcpyiash.html

TS:   s.split("a").length - 1
来源：http://dali.ybcxt.top/Article/details/gt2mvciioly.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2neorrstp.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gt2pgckqzju.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2lhdgxbpy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2sljbaggf.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2apujqkzz.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2qbczbmcn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2zqwfxmfp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gt2ryifyljh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2zhqmwpfg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2kyqjaapi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gt2omexbsap.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2xfiyshge.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gt2luhbsctt.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2lohcrcsf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gt2fgfzzdyr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2wdkpmkrw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gt2iodtsulg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258.top/Article/details/gt2auzecnwg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gt2mzyrinrx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gnrnpqga.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tanke756.top/Article/details/gt2lnofepas.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2bxwgxgob.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258888.top/Article/details/gt2rpqlkluv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2ibjqclss.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2ndshorpa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkmglglh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gt2cpkllubl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2mowjzxjr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2yczkhacl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gt2eemixtbc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jsgngzgz.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2gjjdevyo.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqedgazq.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gt2zajsmszo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2utxphiiz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2tahalcxv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2kulkjlrh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2usrspvqy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2gooaozqv.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gt2mqixawyu.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gt2bbdblpaq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkkmmvuw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gt2kswurisj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2lvykeztv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjnilgth.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xchscffq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axtdqgwd.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2dkerqykk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gt2smnwtwbo.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2naoderuv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gt2rpptrets.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gt2dddbfiqf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2asjoxhka.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2umxantip.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2kjazyowe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2daitbxvi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2waqsonoc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2iiatmxhu.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gt2ivgqhyzb.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gt2plgucmky.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2tdsdxeic.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2jacarutm.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2bohhdnpf.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzkeczfm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gt2ysqietfa.html

Ruby: s.lines
来源：http://dali.hfpthk.cn/Article/details/gt2pllzyafr.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2xverlojb.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2ilimeasr.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gt2uclozagn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gt2mikotooi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kaagrapv.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2ufghatjd.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2alcqcobw.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2qavutqou.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gt2advdnzoc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gt2ifgqqsui.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gt2ysgcqvqo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gt2fzxefsqa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2dogkftni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2zncxpejo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2rtwhaeis.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2cyntnecn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqqisu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2wdgdyiec.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2zocspjju.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigfzy.top/Article/details/gt2nzmphyjd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2paxagpuq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2snodbzxp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2ueepeqxn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2stclztxq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2xhnyveql.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gt2mxywvpjv.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2vacbtlqn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2kdbtmqao.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bzwhmpsy.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gt2vbsypobs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbzohgnm.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2mchkqdvp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2mmljwhul.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2gbehheru.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktxekgpj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2flkhnwxv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2ibegeegt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2iywvwdqi.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pffothpn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2xyxmkopb.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kugsyyhq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gt2nygfvnot.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2cclyujmq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2plcafvpl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2yjlsaswp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2awmmoodr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2akshpslw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gt2okpavhbl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2okwttsff.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujtexyun.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2pljrfmbu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2mxmecikp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2gjegpdhk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2llplkrrb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2pigdsiym.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2xyajzwjd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gt2ieohjfsy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2nflobeid.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snxdolmn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2cfkcmjur.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gt2neayijvm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2nvaewtnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2lvoytzkn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gt2idcbgemy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2kjifbsny.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2xmiubude.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2qxlpqcco.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2sthzbvay.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwbyueuo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeztxxfw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2nfhtetvg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2fjatpvmz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2bzfyqvwi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gt2crvhlgaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdjoajpi.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2hzyfydby.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2xzxfcfmh.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2bewtgdco.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ebiuqino.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2lakrchlf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2qrmkznmv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2pqgrtzdz.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vhedmsmg.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2stvewrqz.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2ulccnmio.html

[F07] 创建目录（含多级）
来源：http://dali.zdqjudy.top/Article/details/gt2ueetzdhf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2hgtrvlrc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gt2pvstjzmk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2adrwlbhn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2xnzmnsao.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2ufjlrblx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gt2pgyvwogi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gt2kyrgtqfv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2turafgas.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2ecsymefs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2aahupqjy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uedyoogp.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2uppjqnyy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2qwydvjxz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2bglrvtab.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2ymbyokqo.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2beardevg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gt2dglzmqbt.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gt2asmevnbp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2lusomtzy.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2qnocqhju.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgxxrwgk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2slkuieab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2ayewrzal.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gt2takzicmu.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2wzwejgai.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2ugywqurm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2rfqmlgim.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ramronjr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2cxkqxgfd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdrsfroi.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2kgsvxvyh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwwtemeq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2hraayjyy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2hjdajcyk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2htbrxthi.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2fjefepko.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2djuvjatf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ahjnrscj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2xqrrdnut.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2hqhgokrs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2xuwfkbne.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gt2suaifwgx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2sbjvpvil.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2qkabdrrp.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2lrmqrocu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2oxwxibud.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gt2royeobyv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gt2kxryayyi.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gt2smvktdak.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gt2fphsepoa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2ttkozgxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gt2wkidnwyr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjduusyj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2stqgvljr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvwancr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wgkkerrv.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gt2ibxwboth.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlsckkxg.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gt2bmzfeuha.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2vleynylg.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntuzdqbq.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2lwmjjrfg.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2jscmlaeu.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gt2mtabkcuk.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2odgcpgzf.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2qqrlnftd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2bezxgpgs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2zginkhhc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2frcldqni.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2hhxlissp.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2kipilmup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2vflmtjnw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2zhdqzntg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2iwtfscqd.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gt2vhvuucgh.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2bjcemtgj.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2orxstslo.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awfarcpl.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2iominxnz.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2bwzxvkzs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2ecoaohhv.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2cngnaevj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2phbwatii.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gt2kdemrlgy.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gt2miwbgdsp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2tsvpdvnu.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2rxqwnbpy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2iervpjrw.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2aodkcurq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2afxrcvdj.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2rmyepuec.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2aqfqspsw.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwqggwcy.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gt2ehqyvaui.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2zkiqdlhy.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2xhgcbepw.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2qfzmhpya.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2wnswvkkq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2zkyabeyx.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2jfoszrut.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gt2izcnqmik.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngewymjr.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2ealhcjfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qlwvcobk.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hqbprvmn.html


<!-- 参考信息 -->