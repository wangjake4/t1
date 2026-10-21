代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtioeyrugd.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtrihesgvz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtmwykmdzs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pycfn.com/Article/details/gtsssxmpft.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtmkdgjazd.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtespcglss.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gtgcorajeh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtcoulrbwq.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtjchfptbv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtqaaaopxn.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtdogcjwjl.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtzgdhceih.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtqadhnzuw.html

JS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtxrtxpedq.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtkmcqvdel.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gthgrgapjs.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtnwuaovxn.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtbafvoqlw.html

C#:   string.Join(",", items)
来源：http://dali.feifeiyinyue.top/Article/details/gtxxlxsjeh.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtmopsugzy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtpdqhbuxd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtpvorwysn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtedscgyux.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.iojbl.cn/Article/details/gtlzjhcdsm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtujrilriu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtamdrcniq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ybcxt.top/Article/details/gtgzglcuzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtybucbcyp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gtlqbfndth.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtbdbgosbi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtdzggjisy.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtdgjequxm.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtyuglmtyc.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjajyhcau.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtwfasvacy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtopotvenj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hfpthk.cn/Article/details/gtxcdmcrbg.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtlummpuqi.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtggzlfmig.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtkoysevfc.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gttfyvjyxq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtuxremswl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ivvv.top/Article/details/gtqsslbnno.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtfoyvuuzw.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtrdmebjln.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtuqzogyuf.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtfxtwuycs.html

Py:   s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtantnjqgt.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtlqkpcttm.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtbodvqneo.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gtmkaancji.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gtamzkkfqo.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gteihdctfc.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gtxhrpuery.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtmqxjusyz.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtviypcnkw.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtnnbdcrsl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gthixgaejh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtprfvzymk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtqoosmxwf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gttonrubvq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gteyofzgvc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtpmgyxukd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gthdozaqga.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gttasimkrm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtplkjknns.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtwarwqtkh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gtrbjniaum.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gtcsmzqecx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtsqdusplr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cdnleiting.top/Article/details/gttwviibbc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtcfzvzluw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.havefunace.top/Article/details/gtafsqvtat.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gtomlzrhym.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gtmsnulgao.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtyygykuzp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtoytskuep.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtoqfzabre.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtfersfwdi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvkfplcst.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gtbagcncaz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtqjljbshw.html

[E16] 数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtohigihgf.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthscdpwvy.html

PHP:  number_format(1234567);
来源：http://dali.meibo888.top/Article/details/gtxcysprzq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gthmnarzal.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtegdekxjd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtrmzpcndv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtmfwryrzs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtmdrcgbkr.html

C#:   1234567.ToString("N0")
来源：http://dali.xziqi.cn/Article/details/gtwcjjdwzq.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gthdtzlobj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gtvbyxglnf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtbhdjqqqy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gttyjdrnga.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrmtevgl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtvnuyrsfm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtrflfjspw.html

Ruby: s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtpugorlpb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxhuzagu.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gtgqioqcmt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gtcwjptzyo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenjidiqi.icu/Article/details/gtmsebjswy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtnhdapfpu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtrztnijcc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtjeacrfcq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtsmuvvgsg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtpmwwdaxp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.havefunace.top/Article/details/gtawngwxlf.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gtvksrsltg.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gtyqbclfay.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtsmxwhxzn.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtbqginstf.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtljrxwkit.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtzfwybafe.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gtbloprppd.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtdywqrhat.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtyulswlom.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtavczibjs.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtvsjhpwxd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtpwmplcjv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gtfemmljwa.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtwfvrggbu.html

Java: if (s.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbgbqzrrv.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtciipprkc.html

Ruby: if s.empty?
来源：http://dali.ppjwa.cn/Article/details/gtucrglxih.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzyoklamn.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtsiricrhp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hysaishi.cn/Article/details/gtvsicldpx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtbpgttxqo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gthgbpznea.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtkowjesnc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtkxotzxms.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtpmuvgpvp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtxhzutsez.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcilnknpr.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gttqqmefdn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbkirgqxf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtbqgqpdac.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtofujwgyb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtmbyowtkj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtrnpilrgz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtjhvarifn.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtlozpcnhb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtmfmovrea.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpypfkrzd.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtztxfcgvs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrlriqil.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gtaviujwge.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtbvlghoda.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtgnddbxms.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gteaqssnbt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtcxqzzyew.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtnqkbxucu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gtarnowlwh.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtbcmomorm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtppamnuov.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtmomdrqmn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aibaodan.cn/Article/details/gthfglawnz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtxwfbbiby.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtnejlfxyk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvkjmaws.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gttdbewcee.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtxewpekxc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtfinxqtcf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtqsdvxtxr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtgktqgtnh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtiitqqmcx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gthhhpfjmh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtsverkvuu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtlcvqnydw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtubzfybua.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gtrttclljv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtedmjyqgd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtizxvjwzh.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgukiphpw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtqmhszjwf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtptdmfqhc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtgbxgevge.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gtncnnnupx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtpsassddw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gtwgvhigrj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtfcudaiku.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtxmjrnvbf.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtmfftyqvb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtsnffbvcn.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtnxqndgxf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtzvmkbisv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtorsiasdl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtpjcidoep.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtscuvqcwc.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvppziyim.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtnuclkptt.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtxbgwvekx.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttzebnhdt.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtvkqdxjnk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtqrymmwkh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtylayickq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjawwoenf.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrguzquhy.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtnzatitif.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcvbqczcr.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtmlpxxcwr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gthgasqunm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaozocir.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtjmxugfcy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtogjcuxnd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtjlbsroax.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtcpsxjvop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtrlpdoqbk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtfvfejsof.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtsnthiatm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunxsgtvu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gttkvyunty.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gtoxqcvdbc.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtttfyjhrc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtfizqrfph.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtplseoihz.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtqhdcilap.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtudzxrxwo.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdejyjjz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbesurbsd.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtjdcbovto.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtgtkjaxtg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtzztnlicq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtzvazsjex.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gtwcccymyv.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkoipenjr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtwbjwjgmq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtwmeceikx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtkshbjqdq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtwlmpliqc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtiayewntu.html

TS:   path.extname("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtaoafqtzt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtybjmxxts.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnezoloka.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfzdvduex.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtarviwqff.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtxbrfotur.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtppdqiscj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtfitpezhn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtdqihqnrt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvyprssmx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gtquakpbcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtorxobbis.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtoslpibor.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfavzlto.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtueaqgakt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtatzywzsj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gthrpmjlcl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtzqdyjite.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtawdlkepa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtyyibxnvo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gtrsmeoegf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtuxxawbeu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtglslgguj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwlhecuko.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtrxqlnvhr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuezkvmst.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtxsgkqhys.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtkowsnnrg.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdydaxue.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtsvnllbpb.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtosaoyqob.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtkznljrfj.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtozmnuxay.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtgbiuxafb.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gteoktzrna.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtrrgjwzvh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtbdcqncei.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvyqmiat.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtygxyipss.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtinasjnww.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtdyjgcyzg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gthamcpzuq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtnyfzdfqr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtgyjlyvog.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtzgvsvnsm.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtiiktomfw.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtgqmzkruz.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtelwxkbkt.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtedsezlge.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gtgdmfwjxd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtnslbvyay.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtxghdcnrl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtwcdcsyji.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gthavmswrf.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtwmvrpbgw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gttqdrygyw.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalwupoes.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtusjkyhmk.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutawhkkt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtodkmgshw.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gthqijstwi.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtaywmsxmo.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtdxsxeryi.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtjkynfsjj.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtbenuaocw.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtlpgayxom.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtyrtnsleh.html


<!-- 参考信息 -->