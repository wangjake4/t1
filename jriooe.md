代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtqmtrvxmj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gttplxipak.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtbiwxaqbl.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtyqnasetx.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtezjnfbhz.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gtjhvgxtsk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtprwkmisx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtkaqowwfr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtckaoohrp.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gtwqfwupbf.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtslmgtuul.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtryhfcfzq.html

JS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtoeoyrbkj.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtmtwnbsxo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtuaahvyas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgdfwxgv.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtfywgkxas.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtyqittqwf.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtsdkceias.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtsemnymar.html

PHP:  substr_count($s, "a");
来源：http://dali.yueranfly.top/Article/details/gthmbhklzg.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtwhesllun.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtdeqizuql.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.iojbl.cn/Article/details/gtfhfzgcsz.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gtlqxbfkbh.html

Ruby: s.count("a")
来源：http://dali.yj202588.top/Article/details/gtocbmyuoh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtkwmjbrgq.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtukmvjzxa.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtyglseetl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtzxzsdmho.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtmqvmhtyz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtggiujvgf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtcasfwfna.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gtrivpmpoa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtspwqvrvp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gtznkgkkgx.html

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtfunovnxf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtbogsoicb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtyajevefx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtcryijgon.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gtbhhydndw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gttwlyubeh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gtfbwdaraw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jqgufenzy.top/Article/details/gtqolfaphn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gteopnhodc.html

[E15] HTML 转义 / 反转义
来源：http://dali.aibaodan.cn/Article/details/gtsvwsberi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xylfe.cn/Article/details/gteezmulqn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258.top/Article/details/gtukninibr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtyzyezogk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtkkshocmh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtltmdlupo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtyuaozdcj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shuidangran.top/Article/details/gtrmospalu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqubctnrc.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtrxrqcyck.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtwgqggmla.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtylyimcrf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gttmblhqly.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gtsneifvwg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tanke756.top/Article/details/gtysquzocy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtqdfipdxt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtrihruezy.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gtgebmennh.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtmgtlypsg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cqqwz.cn/Article/details/gtwqanaxft.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gtlvfoghpr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gtjtrurdnx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtczccznqw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hammf.cn/Article/details/gtgtwsgcei.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcgufekr.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtcoojjmvq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtkkahxtlp.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtykfjtqdb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtepbztrln.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gttfiqgcac.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtursughji.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtmkahefgx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gttjcnobsp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhvujhoe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllqrievb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtuomdyhqx.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtlcuaqldi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gttnzmbtod.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.bjfxy.top/Article/details/gtzjxnruup.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gtnooczgpj.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtfnvarfkw.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gthvnaogop.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gtlxnvdeck.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtpqrgeyqz.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtbwysxpdj.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtalounlhe.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtmawspmlt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gttralwpdi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtvlcpyjvp.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gttjgeynac.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtajxsauqg.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtnpksgmfl.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtlkfkrcnr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlponqurr.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtkrfgqhnu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtmuuyinhw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gttfddbuzr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtjfqhgqtm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtnrewugdp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtskbxqzho.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtxvedpzik.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtpbvaxuul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtxrbbpfxg.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtlydjtdcr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gtygihbfrw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtqyxtkyve.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtfrkynkei.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtkrfvqize.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shzxlz.cn/Article/details/gttreipiks.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtczafooxs.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtaocmccsh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gtowvbqsvv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvhvjjzba.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtusnlnqud.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrjqpuxe.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtxczjqspa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtiubjaqao.html

PHP:  file_get_contents("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtpgnqmxvw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtgbcsncxj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtbadkpahu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtlxcvnwtp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gtacrjioyb.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpyobbwl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtghrdhhpy.html

[F02] 逐行读取文件
来源：http://dali.chenlongwang.top/Article/details/gtxccpnodx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfltstlh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtydvyxisc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gtngecdyxj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtfaxaenih.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtkttoohqq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtmladifez.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwyskosu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtelodojjk.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtgugcgsbv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtcowztbbq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtpzjisxmn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtiokzrumn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsukngwc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtiydkdfos.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtlydueeau.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtpzhntjwc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtsilhdusf.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtcwbucijp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtvgmlgdvn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gtyttiyuqz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtbnktsrbk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtornsoqnb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gthdabqqhm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtvbdmewdy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtowyxwivb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtlaotjgvg.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtsifjjtcg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtqvsirwbi.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtnrlsgvyt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrvxsvhda.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbyshqpqs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtwpmxiznh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtopmwvymu.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuwyfrge.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcrqymjhj.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtyyybsuba.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtmrolthlr.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtvxpwopqw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttatzuioq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtwtkzindh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtrxsrafng.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbswoadgs.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgdswsxq.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtbtnzzzxt.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtfdhkjsll.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtzviksjri.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxxnlovp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtldrfsecf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtrxkgqfah.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtuxmzffvo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtsmhebgrh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtdymkjobc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtmvlhwnwv.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtfvrzdwad.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtyvcxqhda.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gtbzguomcu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtpwscydqh.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtfysndtbs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtothmmzfq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtjixtwylg.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtmbnzktdd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gtwpqntynl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtkhvfddcn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmfpztpiq.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gtbuotxefi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtvrywnnnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtuezczyxv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtnduxievl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtmiixrmnh.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtppvjhffo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gtarxuhroy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gtxrjnpajz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzyltnxjq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkuskryh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtjkyqpqaw.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtlzqiqljw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtrujilbsv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfayxccrg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgigjpmxq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtreygzraw.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtspbtctog.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtvsxihitk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhnmuuee.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjbdbfoae.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzrgvsdqf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtjrscfiwo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtgeslhhrp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtypkuzwip.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtgfvvzdrx.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtfxlbktdz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtfdfkszou.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtsucipzqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtcxwqpgsv.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gttjwbyiay.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtlssfttwj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtgqwzlvxv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtdicdwngg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtyyrlpwwh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuvmmjbv.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtezdrtirs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteqoenrte.html

[G01] 定义类
来源：http://dali.wangdashe.top/Article/details/gtoztwbwje.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gtkxkzzfik.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtihjwfxkq.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtbndlpaph.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkmisway.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtctafgpcy.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gttqbetnyz.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtdnqegyxg.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtsozdmnom.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtvilmcnfn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gttfpjodup.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtdncymlhz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtpkrfpiqe.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtrzyaepzy.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtteuhmqed.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdgrpdnp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtyyqvpvle.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzpimucy.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtcupyvbvj.html

Py:   self.name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtutabyami.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtuxhrxdjp.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtwazupbbn.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gtturnqhwc.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtrrifuarc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtnibhyleo.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtufxwuohb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtedvrlydx.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gtpfotfbhq.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtywpsjgal.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtsnoozemr.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtnqepkwmi.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtbxxlpasb.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtjgotiheg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtpqmyvtmh.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtnrrnhrqp.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtudyeisjk.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtbwehmfaq.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtzgoyaxww.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtamzhujka.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtfnbvuyvb.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtejzjolan.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtedugznfp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtkjzhyqrl.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtijfabknp.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtslzcxeet.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzdhdslc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtetntbaqb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtavysifzw.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqevsriar.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtdjnwzeqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtjbfsbxmm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtndrmqwir.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvruswzem.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtwkwzagzf.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtoycxeosb.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gttixxjuoh.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gtlgyanrlz.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gthtwqklwa.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtzqwlghmg.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtwwjkuysf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtdlidnigt.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtoagxiekb.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlzepyne.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtqmbdunzb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtzzyadufq.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtvstqejau.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtcpuyljza.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtxzspjxsu.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtycgdravh.html


<!-- 参考信息 -->