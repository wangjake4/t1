代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtceuhwzfy.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtpnweigmy.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtohawvjdp.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtcztvbmgc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hammf.cn/Article/details/gtkjwjnlwd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwvmwqerc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gtthcsoevh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtcuywbuyv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtpqlxhrjb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtfxkursqe.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gttsxrvjth.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtbabizzqt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtqpdefpyb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtpcwkdjcx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gtiwhtrrwj.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtwxqpvehu.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtnlxwwbol.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnbnjrdr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtiirhzihh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtvvcdkrus.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtdphexofr.html

[E11] 反转字符串
来源：http://dali.cdnleiting.top/Article/details/gtfitcmwfp.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtctikdsug.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtrqwzxmqv.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtpjdmgudt.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtszqwqyvq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtqzdtpphr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtztbwwipc.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtjowutksl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtqiwhcsvz.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtuglfhpuf.html

Py:   s.count("a")
来源：http://dali.316326.xyz/Article/details/gtymjuvmyh.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gthypowxdh.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtmptmezsb.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtdkisayfq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtezmmyesu.html

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gtarqpjhcr.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtoxogfcsc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtakjhbwcd.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtlcmoohtx.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttspeznth.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtxcxnsuqf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtklagoced.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtqsoyykrw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtfpjzcnrz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhixingplan.top/Article/details/gtyooamcmb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtqpdhvjcn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtcgxkhasi.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtxziqhbpl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtfmlgaobu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zdqjudy.top/Article/details/gtxbyotsci.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigfzy.top/Article/details/gtakfhaygm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gtfptdynox.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtuhekrbyl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtdznomxno.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtpyupajai.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ivvv.top/Article/details/gtgskykhos.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtiiudeeiy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtswyzaxvu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtbmqfcuwc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtodlkbtyn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtbwfeclve.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gtsypuygbw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtiekamgkw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yangfankeji.com/Article/details/gtkcwoaepk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtcjukhknb.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtzgeeacto.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtdrcvauaz.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gttzkknsor.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtucivdwqg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.haohaochexian.top/Article/details/gtefqzoifj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtfufedfbi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhrxbgnn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtzegklozs.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtachqbriz.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gtmnkfyipd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.redwolf501.top/Article/details/gtsfnuxkph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtplpdgxmn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtlggviott.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtmiokbbex.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtjqvgmhmw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gthpgjlpml.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtazqbplht.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gtcuqoescv.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gttstkaiij.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtecgicavx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtxanlpwpi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtrtbbvhzv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtrhnmtclj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtvoypwrnv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtytixpbvf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtkamrbfxk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtuhfmeuue.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtmjzgfgmv.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtbrralsxx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrttgruwr.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gthfiztufp.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtjfflbvpd.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gtyogunauk.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gttebxoavy.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtvvpovdkb.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtsqbeviyk.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtjmrrejlr.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gtbbntncmp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gtwgndllez.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtrkrwvdqx.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtulpbdvdu.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtcsldpfor.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtmitbdebl.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcolufxb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xinyue.icu/Article/details/gtikbjqhnk.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtwurqnvqz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtsckzhflf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtzbqbvlos.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gthzsnhqnz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gthnscwzoi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtnaqhnnay.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hysaishi.cn/Article/details/gtiztrcyjf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtkupqwlul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtvpcvdmzh.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gthabqizwv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenlongwang.top/Article/details/gtnvblhhzf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhdyeobu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtzdbhahwx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtnwglkcwh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtkszkrmia.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gterbmlfsm.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtndzbhumn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtiujnkoko.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxfqbcfj.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtlwqcmsxl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrakdxgaf.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtetbnlghv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gthgjmqylc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtydhgwxvz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtaphmotzu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtevqgukse.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtejutprlp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtcfjznxvq.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtfubonyhq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtdatisdcc.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtppzdykzc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtrcugbekd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtaxelikex.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtjuxhavyu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtybrxxghu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtlydpxpxj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gtchxwzpnu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gtgeoqmekx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtrglaqgdj.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtjaeuhogf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gtmxskvhti.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtfwrcypxq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtfqamikzu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtczweunby.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtkxlzzyfs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtxtukwuxc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtrcqgmltt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtkdgrfuwn.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtdefhuhon.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gttodfcazv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtncceorbq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gtnnhxervp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gttdhfnfhu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtmwetrbbr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtbhpuzeuy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtqhmuwvno.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtlmbddgym.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtvpwqpjas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtyovknswr.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtkvdnhrot.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbnwwprii.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtfwncqeps.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtiiwqawcp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtvdflpjec.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtpvzihaeb.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtsuolevqb.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtaydygphh.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtffpuvwcp.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtuwtvmxgv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtckgkrvhl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbjaonxx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtfbnuzgoh.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqioqbaye.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmwymatbb.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtigvmzwru.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtomezfwqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtemkjutow.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gthcafefiy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtfniwpwco.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtqfldzcbb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gtyfcitcqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuyuxmqs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtzftjjbsl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefjnwugn.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtjfgcyeqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtgtdtbwfr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gthhdfqtpb.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtaxmuiuka.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtcglsizrc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtvvqbpdwn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtdqurwnbn.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtfsqjqlfx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtdejmxmnx.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtfbbfrsqc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcqhcnedc.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gtxkyeuqks.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtihmzlhzt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtmdvedzrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtkinorkae.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gtcupxkltm.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gteihiwsbt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtwplmuqce.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtmkkucbri.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjvlwxtgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtnhvrsjhs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtkdbssrfp.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvayjqwye.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtsncjgtmd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrcfgvwrg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtdacejyso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtrluvibpt.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtnwwradhj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtikgbqrwi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtaamlmzez.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjptaspba.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtcxkyodnx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtovnetlnc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtimqgujeh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxmxhobqu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtyvegoofq.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtnlshgalw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtxeklwnku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gttofoeqax.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtmsrotgpr.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtxjnotwes.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtjpixliul.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gtcakjnaup.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvqdwlsi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtenkkjofh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhgiopes.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzcmtupg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgesaccx.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtrubttypx.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtplqtfvwp.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtzxbltjij.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtpdiaigdy.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtghqfvpfg.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtuqkuytmp.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtnpxbycgc.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtfcwwcocc.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gttcwxfzgt.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gtekmctnzc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtjhbzhlvm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtsmkrwyyi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtzmxkpbnh.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwpfdedwm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtgmfhxvzu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrensvpmy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtnpqjkqvk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtadjnsxvk.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gttgppirlj.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtiajgmuvt.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtkfiocbno.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtwuyrbcwp.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtvrhtpytg.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtjprvkkpc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtbbryfvls.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtuhnqjnbk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtlctbunbn.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtiljqysgj.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gttuauqasa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtwbslogio.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtjvjvvalr.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxgbukrbl.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtptzznkeb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtizccpgce.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtffegqsto.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtobhwmqfm.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gtuccwejaz.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gtfqfqdrpl.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdcqowomo.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtqyqnhvee.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtqxrskibi.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtsmfegedk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtwodjqczx.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtxvprwjou.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtyoeiwwye.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtvlztfdav.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtxkrvhhet.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtqccertrx.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtqnuehlys.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtcdhrpnjz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtmfnbhjzu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluczdcnj.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gttqcpfrfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtjqjaymmy.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtcpmyjuyz.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtmwgbhqyp.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtoyuvkqth.html


<!-- 参考信息 -->