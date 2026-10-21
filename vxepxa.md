代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtuuyxdyvo.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtptlrsscb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtaraerltb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtblzmixon.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzviwadrk.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gtejylqkxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtamzpwisi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj202588.top/Article/details/gtzitltsrc.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtcdaiqgaq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guowangkeji.top/Article/details/gtxrmpnlps.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtmncppjco.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtsyskghjl.html

PHP:  implode(",", $items);
来源：http://dali.dianchejie.cn/Article/details/gthvehhqgb.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtzbahrlou.html

TS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtwjgwoplo.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtaprjyctq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtivnnetil.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtjptdvrlc.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqbefxiv.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtcmyhrlca.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtajpfzqht.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gtomccyqfk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gteryiidfo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtdanslowj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtggtmkwzp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gtzemofucz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.nanxinkj.top/Article/details/gtwsnwdgib.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtglgpcjbq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ehwqpu.com/Article/details/gtfhmoeuhi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtkztexpqr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtuidzvvqx.html

JS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gttvnxfwaj.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gttmbbddxm.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtmhrapkwb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtcewixthu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gthlxxotvs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtdslepckw.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtxoyadnbw.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtnistbqqm.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtmsdzqshq.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsnxhess.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtvrqyukai.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtsrfvasyw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtskezutvj.html

Ruby: s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtsmbwsodc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtwtmumzhb.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtxeasqsuu.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtpgrhxiwz.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtbkaynvsm.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtpckadufq.html

TS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtrthfhyie.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gteoukoyuj.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtgixyffir.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmfdzljf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllckvnyg.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gtdiosepeg.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdirsedp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgfzy.top/Article/details/gtmmsuaiek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtwawwvgwb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtiekekyxn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtkrwugols.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gtvzwpybpu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtwyycuxqg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gthtsbvrqm.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtysuhiaez.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gtaibenuvv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtcbwrttre.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guowangkeji.top/Article/details/gtyocpagml.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhongyouzk.top/Article/details/gthspynenz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtlyhikcjv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtvtygaijz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuanzx.com/Article/details/gtobrabozt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhcpyysx.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtxyiallbq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sxryk.cn/Article/details/gtcjvkejsr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gteqflasnt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gtgonvqflq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtsniedtvp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gtbeqxtclk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtmpimmrka.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtklhkuvzn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxalpodqw.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gtroixxllm.html

Py:   f"{1234567:,}"
来源：http://dali.meibo888.top/Article/details/gtfdikorfg.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gtagzmwyam.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtucgzcfep.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxteilyj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtrobtylsg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtvobumsio.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtsbudmuif.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtxdbmrcad.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtkhuvwqcr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmblpalau.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtetcadnzg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtsvhmjibh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gthtmdlzrl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.iojbl.cn/Article/details/gtunbuipiu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtbwchvghd.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtbmfbdivl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtkvuixlqn.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtuyxmvcja.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pengpengdd.cyou/Article/details/gtjsmphnbc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtzavjyslf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtrzwobcov.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtditrjdnt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtfnwoajla.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gticwamnsw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gtnhbcnxxv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtdsphdobj.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gthxjuojnl.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gtepwfobdj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrjobbfqn.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtsctyhask.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtxziyvhqw.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtoczqcvqa.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gtgycltlqw.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtxuifaagr.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gtczkdfdhd.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtbqdtqdqf.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtboqicsjd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtygnwqpaw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.vqdsnc.cn/Article/details/gtglnyutoq.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtwfogjwrj.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtbvtpywox.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gtjqsrktsy.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtvlpnunpc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtechuuynp.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtfictlaby.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtprfovcro.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtvkwqwgow.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtajdrtipw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtlralhiro.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gthyyxzjpm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gtbxnkifhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtwmincfaj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtnzyrjpvw.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gttkecclqc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtuaanfycz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtcxnfxsmz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtgvownock.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtafqwmtyh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtxlzowuic.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtbjlxmclq.html

Ruby: s.bytesize;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtwryqwfyz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gtcxfiikhi.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlyykzlxp.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtgqvhxhct.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttdndqnks.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyqukuhu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtdxruvrsi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtuzsrskho.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtcrdcvnmq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtcfiawdva.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtsoavursp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gthrrkvfxd.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqsreyxtn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gtypcyoayq.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtbayworee.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyxsypfq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcqgxwghf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtytgodeme.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtamgmnoyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtcynpkkag.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gthkubdhqk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhmtqmuq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtcjehhjqw.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gtvkentyyg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gtedpenfow.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gteczkpsfy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gttkoukgvp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtkdfkdfzr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtftglnfsa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbjrjuki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtdlwabtee.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtemfpfsym.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtujbaobsd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtgshoggiv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gtmfxsngms.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtyualajdq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtadgbjhdj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtwwbasorz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtlkruepqx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtlvcnehkj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtjquhyhwi.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gttzagdnat.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtqcdcpluh.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtxucfgbii.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaxzuhzzh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtreaemkqp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtfbodktsa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtinmftznl.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtexogsbvr.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gthffvewus.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtunkodysu.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdcnahflh.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gthagmveao.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdvqmjmjx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtuevicfqv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtopyyjcax.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtiaqcuxaf.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuxdtxeho.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtjqsecfzn.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtkufsbiza.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gttburelfp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gttdqbdshz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtzulpzfev.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtvqiqebih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gttliljegg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngwrdrmh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtcylshofa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtyfnhsalc.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gthfzmspvx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtmmmkikyo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtayezfx.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtasrpksok.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtlgiignzr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gthznhzxrx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtivrqlbxp.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtbwcabbpd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtfbmalgwn.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gtoccbnnto.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpppacwev.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtzjvlykyk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtsdepehiz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtecqcgckz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtcvnppwwp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtmgnurqal.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbqxwcsgu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtyhgdczrh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtzsoowcmu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gthwzsjkyi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgodpjnnd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthnwffnyg.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtsctfdjuz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtqcbzvhxl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtztgkynfb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzdeeofnm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjigixojd.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtcceclvmo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtumuiudmv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gteygmggwy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqtackxmn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnvwdchdg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtfgztvcag.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtiuocmkgw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtgcgimakn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gtpozbgnbd.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gttzihknpq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtddycykox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtytadvgtk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtlwzymfvc.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtcooxppoi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrjhylwc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtjyxzfzbu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtawtqcfwa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtnjyfhcxg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtckrwmydu.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gtmxdgpkne.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbhvtiajz.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtasdzldwl.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtehtnvtuu.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtztqmlkpx.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtxvgkleos.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtszzhzgvf.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtfiyopsae.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtlbalicek.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtihiooyax.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtdsorgrrc.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gteqfjdeji.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gtwtnenneq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtiueukdhv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtjnpvoxdd.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gthhtmqubd.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtwgmfatdl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtpbchohat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gticvnjlzw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdqvunpig.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gthcpvkvtw.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtezaesgck.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtvcypjffv.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtuebgwgqh.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooxshmiv.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtawelwocd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gtvjjjfchq.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtjrvabpza.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtcthwdkqb.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtrkdapaqa.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtpgrwjciq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtarqovyli.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtsfdobyze.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gthrljlpjk.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtmtxhrhfh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtolblhxgm.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtxejpyogd.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtgxqpmarg.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtjfrjuzpf.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtwbhhfblk.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhfrhffo.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtjjizrguq.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtvhcwhumx.html


<!-- 参考信息 -->