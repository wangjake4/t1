代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtozbhcdfc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtxfizkarf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtglydvdsl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtyyfkqwjc.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtpucfwzuo.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtrtjkgnhe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtwrpmzlei.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtwegorhye.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtedmncvbn.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtogixwvqm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtcxljwqos.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfeaqvkmd.html

Ruby: s.split(",");  s.split
来源：http://dali.fzhhl.top/Article/details/gtxnismhlk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hammf.cn/Article/details/gtrrrgkvnh.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gthemzwbmn.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gtgyxvfgfy.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gteutrqzww.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtermeijky.html

TS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtneroziwz.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtblysisdy.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gtihspzkgn.html

Ruby: items.join(",")
来源：http://dali.xziqi.cn/Article/details/gtjnfsivpx.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtpnlsifpf.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gteqxximoy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtmgfonzkc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gtdtqbtzpm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtcrudmjsn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtogtwuhzc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtlqjvspwd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtdbisyqvz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gtmtkxakjf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daxiang520.top/Article/details/gtovqlplnw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtlmkvoauq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtlhtaaqnu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtfpwcniat.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtesryfkrv.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtrsfdbdla.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtijexmrbr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtstwlsisu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtitofdtxa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtspvcjrii.html

[E11] 反转字符串
来源：http://dali.redwolf501.top/Article/details/gtsudfbjnl.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyyxplyy.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtxbihqxdw.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtevteskvx.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyimwvda.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtknkdqrut.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtlmzdvszx.html

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtlfckieim.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtswyqdtgy.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtpfecwdgj.html

Py:   s.count("a")
来源：http://dali.hfpthk.cn/Article/details/gtagvwsscm.html

PHP:  substr_count($s, "a");
来源：http://dali.cheryme.top/Article/details/gtpqgqbetp.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtvbccfzjz.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtyluqotct.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqbvxiob.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gtpcqxgtaw.html

Ruby: s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtkszgedhe.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuetiantiany.cn/Article/details/gtroiymojm.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtlrqtbpqb.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtxdgyaoun.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtadzpdoxc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtfuwiyuuj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtisuuwxff.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtzixdbxkg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtfrenodix.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gteajhkbwh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolzqegdv.html

[E14] URL 编码与 Base64
来源：http://dali.andypj.xyz/Article/details/gtjvkutmlf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtcfnuowgv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuagpszp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jlsjyb.cn/Article/details/gtxhgaolte.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daria6918.cn/Article/details/gtmvokwmth.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtaymyjfbu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtzrjvvrbh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtcipgmgxr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtmpowvnrx.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtyyjwvcgn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtdzwufygq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtlarjzlwj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.andypj.xyz/Article/details/gtxhbilufa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtecwcvyrs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtqrjrcgxk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtwvcoqwrh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gtdhlhjcvu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtexcqbxsz.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtjkwyiakv.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gteglmwaqy.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtmdollimi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtounynxoa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtvdkvgdtp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfycokezm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.haohaochexian.top/Article/details/gtowgxxkzx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtukuqgcuo.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtpujsfxnc.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtdhxtveat.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtjpcbampx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtzngjoiyn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawitaoxx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtcvhqfxkk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gtgzuhlzop.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtgoavwcok.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gthwdzjdbg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtmnnbtztw.html

[E18] 模板占位符替换
来源：http://dali.jianghu66.top/Article/details/gtcbqualwa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtbreoufem.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtunqwgrju.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtbwfhmywb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtvewndsts.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtgoiwanpp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtnbwabjrp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinqigufen.top/Article/details/gtchvxguhi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtikauwjxy.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gteasseklw.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtommlkikm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gtdrnugqkh.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtmkyvotjd.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtkuoshmge.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtrpalaifp.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtlconsorv.html

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtxopbrhoz.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtcekkmryj.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtqzzniaxu.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtdatixoct.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenzaomai.com/Article/details/gtwukckirz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtrzlirvku.html

TS:   if (s === "") {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogleucgp.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtwdhnrvjj.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtpgpwnrqc.html

Ruby: if s.empty?
来源：http://dali.meibo888.top/Article/details/gtjjmocjvc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtmiccjnil.html

[E21] 超长截断加省略号
来源：http://dali.jyoumei.cn/Article/details/gtpoouuzeb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gttkwewihn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtriplqysx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtbrnkmzrh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtyoqwcqoe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtrihbtser.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtkolwlizd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtjuyqzypf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtundbcqmj.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtorisrxug.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtojudpenw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtaxsejniv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtqncqmajg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtbuinravx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gtwnlhakpt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gtqiwclgtt.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtmtjvbpti.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtfajmiyis.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgmmbklx.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtmpyrnmjf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkkjpcgmt.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvaxdpszh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlezjrksj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtazvrsknv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gtgnibtjnp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtofgdtbar.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtyjcolyrp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.birdmap.top/Article/details/gtzpyjohmu.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtrlqxcwvj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtnwnhaynr.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtaqvlejgy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtzljpcklg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtrqhvuoqv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxpwaxwyn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtmmjrxonb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtmphovtsk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtptirbnhj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtqllwjizz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgwpszcjx.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtpctsifyp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gthdwcwkao.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtyghhkwry.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtqxxevagh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gthdvlnjvh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtooolfdkp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtwhrpbvdl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoopobrd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtlcomdgzu.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gtaqijzefs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtomytagjo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtqctcemua.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtperbgktl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtybqwtmvu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtmxmndewm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtqmtqljyr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtidsontkk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtodqtuetw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtoutnsfad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtjrnfueny.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtepetwxaf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtiuwscyib.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzhljjyw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtdatstwwr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtbqebbpvn.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtdlkazxzn.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtyvliphns.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gtogrhjoqe.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlcixfsgk.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtrhmuoflo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkfsjlbhs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtihlruxcl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtbpylmskf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtlzawqwdl.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtrhtaaytz.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtucxwdwnt.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtbsarxnjd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtmjskwcnr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqczzmue.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gthymqyqwj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtwnrfhkkm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtqqdqadiq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gtqopucnmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gthnktcvxa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtcrueuues.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtmnjhgybw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gtlmzshken.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsdyoelxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtymlvjqig.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtgrhbxflw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnohbgdm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtlinxzjmp.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlciefeta.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtpuasfmpf.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gthquyhanp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttdbijbpe.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtonetfqhc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtyicxlnum.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtkmozyout.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtdaaiswti.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gthiqseiuq.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtandfeehe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtszwzgyxb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtnwwhiuew.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gttgqfboxz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfjzvebzg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtylpxemvb.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtusanngup.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtbjjmztdf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gteypiymxb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqqfpicg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdsuiolqa.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtjdujukor.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtgkbrrsyq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gtakidcgqh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkxpavtnc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrjbafwkd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gthkczytia.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gtjyayluda.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtieuysuap.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtegqeblot.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczsjnxul.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtkclkmywn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttevgomcd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtwglnwfkp.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtuygsrlwq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtriebhgnv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtirodlwqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtklupcnge.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtyjypqenz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttcnlatcy.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gtrxzmcqkw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjxcslyju.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtqhmyfuka.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtbycufyyu.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtskctsyju.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjgftpgst.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtmygabikp.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gtjnhbamcw.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoxadaow.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtslcirxrp.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtlatkmruy.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtdvbwdcwa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtjraemjfm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvhhvfkhq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtntteqsbn.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtrfmcytwa.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtguqgeacy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtanvuglyz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtasctzlwb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtjivprswi.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtcgujqcfi.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtdzquwvrj.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtnljorojd.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtbbruhxxo.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqtcicme.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtzdkowatk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gttxdmkgyo.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtpohhznis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtiuwyneyv.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtrikiwown.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtdgusjcfl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtozxbveem.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gthbxthgva.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtkahqbv.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtsfpqevtw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtbpkryctf.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtqhxxoiek.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtyyuuudkp.html

[G05] 继承
来源：http://dali.havefunace.top/Article/details/gtnaelwzpy.html


<!-- 参考信息 -->