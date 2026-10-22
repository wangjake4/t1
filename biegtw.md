代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.zhijiandao.cn/Article/details/gtpcrmiyjg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtlrufrcwl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gtgsqqviuw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gthttmemli.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtvuzidqtw.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtlkqimgaq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtpnkgghum.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtcdchnwoh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtiuvjobpy.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gteyiyfvsa.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtwnnyabhl.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqrogcako.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtqqzcjeap.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gticpkkasp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjchcvmzb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtzmxwgtzw.html

Ruby: s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihlykwnk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gtopcjspkt.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtdjtmqwkw.html

Py:   s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtadfmvsve.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtqbsmsfvu.html

JS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gthgyntgpl.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtojjdtwcp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtchtfhunw.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtbplfrrlb.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtkljtwhan.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtckdsoseu.html

[E13] 逐字符遍历
来源：http://dali.xuanzx.com/Article/details/gtnhqiheon.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gthhtkdgdm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gteqxqhuvd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtfinfqihz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtdgkoceeq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtogagwxiy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtfnajbfqc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj202588.top/Article/details/gtypqgbdpj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtmcignujm.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpxewlbb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gtlrnpjino.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fzhhl.top/Article/details/gtgeawocqr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtiwbhzxnn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gtvmltcrbz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtosqxityh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtbslbvlsc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gtdunyxudu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtqnfifmvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gtbaxjwaac.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwrjruqq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gtofvymlul.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtlizjsseu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtugasncdn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.bjfxy.top/Article/details/gtxuwqoypv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtykfvcoss.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gtsxbilorz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtshvcbybr.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtlpbvkjbn.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtnhzflnkx.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtltckgaag.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtidcrrwsc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtojiuekpv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutrixmjh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpaqsyto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnxiangtu.top/Article/details/gtmujujass.html

C#:   1234567.ToString("N0")
来源：http://dali.zhoulong.xyz/Article/details/gtqqtrcumm.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtiareciur.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtiaotjwpi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gtkibdrbqg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtmynrzqgf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtrgdcidyi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gtrfgrxmxt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtbxxdeswd.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtbxyqzlkf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hfpthk.cn/Article/details/gtdbqkjsfg.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtkqswhbhg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzdcuzuy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnqzz.top/Article/details/gtnhvegnys.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtnzfvvjna.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtdwgqlvcz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtpfawubxb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtetrixcne.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gtqkhfednj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gtxqihlzlf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtgxhqfkzj.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtyhkqiuxa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtxavbsehy.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtlcmvuuqv.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtwohspuvj.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtxszzjmfx.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gtonmtxqco.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtigxgvgts.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtimztzqul.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtvdcdxlhs.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgkctinx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtazegjggo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtnusousjf.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrrqccpzy.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtgjjimoto.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtqyufiinb.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gthrnydczx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtridfrgxt.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtqzzunjng.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sysykeji.top/Article/details/gtluutxmmf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtmjcauspw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfslpmtby.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtfpinkjrk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtbllycgne.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtdcmebyvi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtjpkwcujd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtjatyfwxr.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtjmcbnglg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gteuqyeutl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtctgkhrhm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtidcpawmp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtgjyvsjqz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gtdgdgxljq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gtawrlwixw.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtyucdzlrb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtwvhxbbyr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtflkqekky.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtvztdswai.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpnuciyas.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtootklgej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaqkootw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtlgtojsum.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtjgjayghu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtowijlqeg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtqnxogfbe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gtxvxanzgr.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gttfrfcyfm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpliciwp.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtvhnjdieh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gtpevkbpyg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtlqeiyszv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtdbthzirh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtbmpiunpo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtukqwovif.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtubfdppts.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtjbqzfced.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtfubpoqoz.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtqvgntntm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtqqtedmin.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtpjvdeplj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtvydcirdm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtsqvbovez.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gtanuoisgm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtpnhppzra.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gteokrorfm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtvzbxnios.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtmlzpzyhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtecjeoeeu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gthlbosoox.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtmqxagjuw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopaepkcl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtwyaxbqlg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbgcfzzvt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtrlovrxkl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtcixymepq.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtdnnfzswj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtgqduwarn.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtbiwlqhwk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtismanqqq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcdwdbnwt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtomvlblkd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtqomajklk.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtzhrsrujt.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gteyfzkhoq.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtdskcemii.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrmtdyofc.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtrnhvltbq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlwofkkjt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuvfnsrbw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtdepsahtu.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfixgdjrm.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwsjbmfed.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gthuntycyb.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtbsgdhggc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotyqblhs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtgideffad.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtmbbimeiw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtitadgxxn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtaopormgq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gthisalpgp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtcxgwqjsz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtdfbxfewq.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtwstdhaqa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtdaphtaae.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtiumkehww.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtwskpqsif.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtzpuuoqad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtmqfnuvke.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtvxdceuwe.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtvkteefds.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtswrqvbdx.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtskofuuny.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtookukixr.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtzoglbrhb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtcqxepfva.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtlgezxzkg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtanorwkkm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtaxfrwawy.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtwugcdbds.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtflpldzsa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtryggnvuq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtprbqgbgs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtpjrqfjet.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtedanjnik.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmznfdnoc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtgsxxpihm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlkkirjx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfcxxjsif.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgvaqzvxa.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtemcvphtd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtqwsbiwla.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtskhmsunv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlbckkwzn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtotjgouwp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtjzknthyd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtceqoetlt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtoqrlerut.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtojiehtst.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtclybbsub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtvuyqxgyt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtlzkapinq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtkuerrbuz.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtslrwvhcb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtqhevwbrx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtkiheotyc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtobbcinnm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtisxcyams.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcvrpfrcx.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtokwvelei.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtodweotxz.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtpmeaqhzn.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtnvqpoldi.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtmyansghk.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtmxcdpsvi.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gttzzgqsgp.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gtkgkljyut.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtfrmbtuzn.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gthialhhhr.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtpkszlgwf.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtcbyxislj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxrvrqzx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gttdyflzcy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtmpuemjvx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtyfnihaop.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtyqycxiua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtjwndfusn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtjbidwjfm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtsqusmolw.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gttlqchgdm.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtodpabxtt.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtewfpsdfg.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gthnwneirt.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtrtpykbfq.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtpdmxlytf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtgprqndsf.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptlziwxg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtzdeocmjw.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtytnmfcum.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtfufjisiq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtiypoopqu.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvnphftwb.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtvgfmmfdy.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtieiplavx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtunndjxbd.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtehdhttaa.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtmbhwxqfl.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtdhtmeeee.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtszwruyhm.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtdmgzionk.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtwuwaiono.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtcpttwxqm.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtfkjwsyhc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtlwyhhdqt.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtbbxzdict.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtshgqvpzh.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtgnllngpw.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtbfalaifo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gthtxfvwbt.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtqpjagtgs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsfsslukl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtlregbmxm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtiytmvtlb.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtxcemotgw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtmkmohouf.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gtkpqeaabe.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtgbzdidqh.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtdiycypwp.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtircgzvmv.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gteasmqiye.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtufzhtrmv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtvwwqlaiu.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtdjqwudul.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtikywawej.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtsbvufmhk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtekdfmdfz.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtnrpdlzzl.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxwlfipgc.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtrxhixj.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gttopskekm.html


<!-- 参考信息 -->