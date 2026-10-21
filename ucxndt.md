代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gtckxwvwhm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hywenlv.cn/Article/details/gtbovhpfqq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gtocrdjxgr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtedyhhqda.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gtfuhkmira.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarngqttt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sxryk.cn/Article/details/gtqfbafbxh.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtblxztntx.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtwcvsgsjs.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtxkvvinxv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtbghoxvms.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtzpovozhx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtjhxgdrll.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtvipneivi.html

Py:   s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtvqjhteby.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtljpvafky.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtndfxknzs.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtjhkafswh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gticgmsrbz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtsnnakgps.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtamqigpmx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfkrabmv.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtqkhqduej.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtnsmnesoi.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtbcjsiwer.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtldzcequn.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtuozvtdlc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtxzjnxcyq.html

Go:   strings.Count(s, "a")
来源：http://dali.fengsongda.top/Article/details/gtbojbxwdn.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtsnurhdtn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtwgvyajko.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtiqiqzluh.html

Py:   for ch in s: print(ch)
来源：http://dali.kuanghao11.cn/Article/details/gtrgscalzw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtkdhzarcy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtmeagduki.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtleiddowq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.316326.xyz/Article/details/gtuujevlkx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gtrlpfrvbv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtmhgpaaro.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gzhubu.top/Article/details/gtmhctfdid.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gtzqujppfh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtxlrjxvyo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtkllpriab.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtodkhivul.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gttmszluag.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cucudq.cn/Article/details/gtnghsysdv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.mhx1999.top/Article/details/gtvpirvwtr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtvxpjeryo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtpfgawlhq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gteipismht.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtgzygmtuf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtzzxwetqu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtwewytobl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtmshgqrdy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtlrwhmxfl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtysscapwa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtwxmxfvuy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gthbggogqd.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtbgtizodq.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtkgzweobi.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtaygnsbzw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gttdfezxvr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtzwdbzmvo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtbomynphz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtbhlfpxhp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtsjlxwtli.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gtchnzuqzs.html

[E17] 首字母大写
来源：http://dali.daria6918.cn/Article/details/gtbfsqztuu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtutfabxph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtdqhgdrre.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbcpqgqbe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gtgdzkyznh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprqlxooy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtbmqknmmu.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyuseqjf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtwxeltxjk.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtyafzjurr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtdrffvpxp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtlofxfydh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtffmsrybz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsabnbmxj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtmgozjbxm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtitqqwzoy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gtyeydephg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhoulong.xyz/Article/details/gtprinkphe.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtijllddqz.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtbzeovnfj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtolxmtojo.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtrfhlrpmy.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtnqcbotkb.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtnxfbwymn.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuanzx.com/Article/details/gtohcqpbjv.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtaplezrfp.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtipzmbkem.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gthvbfikdk.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gtmaaxluot.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gttxedjrdx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtdosfljcc.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtmtxpgvnv.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtarleqsmd.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtpuopbreg.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtxsosrmve.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.andypj.xyz/Article/details/gtqvjwcbwt.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtshxvzqkm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtuheohvfe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtosjwseum.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtckdosccj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtejunokvu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtceyyicrt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtdcogcfdt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtpuzwzarb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gttkxxrybe.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtdgfxdlej.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtpxsknceb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtajezfmcl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtcdybfxox.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtatfobscn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtspjihztc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gtwyssjtuw.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtsmnhuutu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtzvuhtdri.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqeizuigg.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gtarcwaicn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgfsmuczw.html

[F01] 读取整个文件
来源：http://dali.ehwqpu.com/Article/details/gtnnwsoovt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gthfaxkfti.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbabisljd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtgfiovrdc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtiipxvhzk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtcuzsrrbw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtrpufykza.html

Ruby: File.read("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwcuuiukd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtvgfarkxf.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gtcniosjoe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gttrctgfsy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcvkeykvb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtclifdwxu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtvrhecagh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtrnpstysq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gtmimfkjtv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtgzrmwtmg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtjizgzmjx.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtbwxuzznc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gthamwdrjo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtoxjocndb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtdfkamnca.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtftcrnpyr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtxhnhmzra.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfikcvau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtfupffpgu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtatuoqqrj.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gtimxkdzex.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtffnrkjzc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtyfegikcq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtarwzeaym.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtqjwbaaua.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtgaqipihz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtlnzabcyg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtexzihbbg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtzybzzaok.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gtdlugogcx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hammf.cn/Article/details/gttzbaocst.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtzpfnuhtm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtyagzjiih.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxbaoyrxn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtdnktdkpi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtoobdulxx.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtyfbezzjv.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtnapqoxtl.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtazccbmuu.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtnnsvajtr.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtucxrgdwm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgigbbqbp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvhlekrqe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtegurfbrt.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gttftycctr.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtebnbqwrn.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtuqiwstqh.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gtruqpinkb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtqxyyihps.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gttearvlol.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtzswiohli.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtuuxrglvh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtbwriepcs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtsnsutums.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtmvzziupz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtizyheoei.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtaaoleaum.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gtcewselan.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtptygcmdt.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtafyrxycu.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtxpbsnxnf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtivisgnob.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtpijtknvg.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtthructma.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtajylsjqb.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtfxdszzbt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtsipfsrrp.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtlffzvmkq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtubrdqzlw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gttrmictxi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtckfbyohk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtmoimkwwb.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxzzlzemn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtkwoswvxx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtuvuccoup.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtexbzndqp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtnryasrna.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzziutsv.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtkqawizto.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtqjswuwrs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gthlycpufp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtztnrtrqc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqgyzmckh.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtwaetdlrv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtupftjogy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtctcbnydf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpuahqzaf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtfgrdiqxx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtkjwupvaf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtfibzioag.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gttjgtiruq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtumggezqd.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtpfuocxwh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gtwvxpuece.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtiualsylk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtqszlzvfe.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtiwqmxbzd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtxyrpdvyr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtpgpswzdz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtrouoodyi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtucyodgdu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthfjwozpa.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtschsdjnz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuzelhdfe.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtxqkwpuhr.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtxajojlcz.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtpnsnqmea.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtabygrqqd.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtrrqqhdvl.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gttnchrpht.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtwvptpehg.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtysdcozgh.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtfvgzhbre.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqgjavts.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gtehwgvvsj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pycfn.com/Article/details/gtpvqhzdhk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtauqifyrq.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtzvoxeyny.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsvssobxv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtbrujrjtc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtgnjhqknk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtdxunstyh.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtfzsytmsc.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtuxuztlqm.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtiwdxosxi.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtgdhetlps.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gthzoyuqmd.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtvclpbjih.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtqemtbkqx.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtghbowmtq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yongpay.top/Article/details/gtswhyadiu.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtfthjmuon.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtxcnzuxrh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtryjdxgaw.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtosksvuqc.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtzmkimwbc.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtxqpjngiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtdquqesgr.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtvpeahtaq.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtitwiedwb.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtmwrimlrk.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtwjrjeoic.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtnsfwwrbo.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtybwtvcdg.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtdkjfejll.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtnzxodkxj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.mhx1999.top/Article/details/gtnzuiedyc.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gtoeynxcms.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gtxbossbrc.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpfaeuvi.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtswqpumyw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtbixdupjz.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtftruasno.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtryehesrs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtdlhwfthl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtkkwoktcz.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gttjxjxeyc.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtknlmfluv.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtopwrhhks.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtnnmuyaog.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gtxeewdvby.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbvjpppv.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtniwpbbls.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtratlllfq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtgqkctdxj.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtfyotqqjj.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtemsvmgdn.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtkyhuneav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtivoamtvd.html


<!-- 参考信息 -->