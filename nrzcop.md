代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtdnubhqcz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtuiagpeoc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jyoumei.cn/Article/details/gtzpidqwnb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtkuuaokjz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gtowmnhnoi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cheryme.top/Article/details/gtjyrqmevq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtagehnhkp.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtojioavwa.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gtqymvhbyr.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtcdqjhkgf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtckiawieb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtkxzhqdod.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtmpfasfse.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtquyoegvu.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtdgzvltlv.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtqniyvysd.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamaznshx.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtksqxeqoy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtsyamkytc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtgmcjkwqr.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtlturykxi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraeczvfo.html

[E12] 统计某字符出现次数
来源：http://dali.wangdashe.top/Article/details/gtudtbwddb.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gtzsjhiqzn.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsupegzk.html

JS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtorkkypow.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtughfnjeb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtaylmzlhi.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gtyswgsdig.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtqhtzylao.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaklvswwy.html

[E13] 逐字符遍历
来源：http://dali.yuanzhike.top/Article/details/gtbgwbqzil.html

Py:   for ch in s: print(ch)
来源：http://dali.hywenlv.cn/Article/details/gtihfyhtal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zdqjudy.top/Article/details/gttcooisox.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gthtzompmp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjfajqedw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gtryfylctm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aibaodan.cn/Article/details/gtttlndotz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtdriaqkrr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtaipcsufb.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtrubysapd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gtempwngnw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtnonhndim.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtsppnrueh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtsvefzipd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xziqi.cn/Article/details/gtohtljnuk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gtncfkerqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtdfyyyxke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zycfv.cn/Article/details/gtdtafdntx.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtntpaujie.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtncjkfacp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtuyjkkvtj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtdjyumdit.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtfkfxwxop.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gtglfchama.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkshrtsjm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtstpayxiy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtklfkfzij.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtwogsqdnz.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gtbqvkulvc.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtttjdyrcp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtqpyavoyo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gtuhvqbhhv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gtzhdljpby.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gteincfehg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtizmhsgvo.html

C#:   1234567.ToString("N0")
来源：http://dali.cdnleiting.top/Article/details/gtphvxbkht.html

[E17] 首字母大写
来源：http://dali.jianghu66.top/Article/details/gtpiueqqmz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtklnpugdw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gtaqsuvxut.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gtveflbllo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtuctmjoec.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtwwbhtmwi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbladunus.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gtudlwoqfq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtetgoofoq.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtxzqhebrw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtyrfucahs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtvjqnyksw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtjhppsezb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtvcnaskav.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtchsbhqkl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gthsqlmosv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenlongwang.top/Article/details/gtykmtiple.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtogphljxi.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtrwxvkagy.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtytnzebrm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtrcmqbnkh.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtomibrppz.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtpackcekk.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtsazbzzwe.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtwxwvligg.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtgzifjqsq.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtsvnorxpj.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gtazvddxoi.html

Py:   if not s:
来源：http://dali.hywenlv.cn/Article/details/gtvljyjvwd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gtixiccxrr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtgqioroui.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtitrnhttk.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtomojnzll.html

Go:   if s == "" {}
来源：http://dali.zdqjudy.top/Article/details/gtfwuqtjix.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtpjqatgjc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gttucdaudz.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtbqatmkxr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtlnevcxcp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtmtngrjyy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtgaqzypbc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqruwnhrn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtowqelcfe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtpqntudqq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gtqanrbmtb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtaamwihqi.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtvflcrnaf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gtyrlhxdzf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtekfucoid.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjztovgl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtvchecyfz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtehwgeqsc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gthyuxkhey.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtwdtsokxo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gtdietrcsq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpwvjsnya.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtrlisomue.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtivmgzvzy.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gttqpzvzho.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gtdjozujch.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtnpblbtxg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gthzlkikfa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtxgnaukmz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtfwruvqro.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtpfvsqtls.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtsqyukolw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtkhdqoppf.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtvtdjxpul.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtshzxjryn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gtjjpssyho.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtrfgvikvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtlsmtkyyh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtgbrjgipq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtvafsfxoo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gttadfcxmx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtuvfobhtr.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmmzykpe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gtoqqtuhlo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtevftrpcu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtidzmfrsz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtiuuyyxzj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtlywoggxf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gtezcxupvh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gtvivkmkpw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtdbirsjpa.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtrvivqgou.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtejnktroz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnqzz.top/Article/details/gtlibhjddd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtbxzdtrlu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtgoiydxoz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gtxljbhptn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtjvoztvpe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtbmryokij.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtafltkjdu.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtqgwprmzw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtcrdrupov.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtnlcwhncr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtcvubgonl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcgajsvau.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtocltgpme.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtyehkizin.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtdqdlwaqi.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtuqtlwcts.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtqsgpurwc.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbnujtmqx.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtbsasptfb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxqppyrcl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttpudyigx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtvuzkppuo.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvowfxxbb.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtfzdkkwch.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtbzgdpsqj.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtzjfbzxvi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtuprsxkmc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtvapbdjfi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtepghplfy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gturskkgui.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gttoiyiudl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtnocumnnv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gtngnnvexw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtmlroxbjh.html

[F08] 遍历目录
来源：http://dali.wangdashe.top/Article/details/gtgdbjuoxi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtkpssawxq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtvrpnbltp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtlqpblzfx.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtkkqqvafo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.vqdsnc.cn/Article/details/gtdzusyteo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gtjihjyxig.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtbldujqvu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtadvwxsxn.html

[F09] 获取文件大小
来源：http://dali.yj20258888.top/Article/details/gtwxetxowu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtexezptse.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttinniewx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtkerjdiin.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtozstpash.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtvuhfmasf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtvmkavcsw.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtfiyvlaeu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtvcpbfxtq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gthzkujqqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttlixcedg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtpntclbjp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtomkpuyqp.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrojwrvwe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtlklxtzks.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtzghbtnrk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhxmrulf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfnbdxrma.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtuqweqpai.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtsquncoqt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtxjzwszdj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gttnlfgvmt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtohfgbhtd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtxydukguo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gttvrieket.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtmvcyohsf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xylfe.cn/Article/details/gtbpqpofhg.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtgnuviliy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtmhhjzpjf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtnbuzuboz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtperbisul.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtecrsnsnu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gttipwhuge.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtcpoayrof.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gtsobclnip.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtipwvxiut.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtaxvwwcjl.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtysgubwnb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdkspbnfk.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtlipegcbf.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtxbdrirlk.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gttimkwcrv.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtjljbddtj.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtbtteukvm.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gttyoicagt.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtufnzhbvh.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtaqxbfjmy.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtujztobrf.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtyakloysq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtdojlajax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtcthvbriu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtvzfuyfav.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gttqfhohhc.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtbjjpkoin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtkjgxrvcj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtqpftdpcj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gttabnrvqz.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtdhblwtbt.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtdaldjkkb.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtpscofyht.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtadmgxxop.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtyfkjvmwy.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtcxwlcsxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdqlowtj.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtboimyhhj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gtdkqdwksv.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtatoesoqf.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtrmaicbbh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtajcaoyjp.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtmhyqubfw.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtaxptqylz.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtlhhbxwhr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtkqvdkdgm.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gthmbhiuwj.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtfldxxzjo.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtvizhigkd.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtsldevnia.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtymktbidr.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtgkpkbxoo.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtmemhicdo.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxpbliuc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtwpjbkbvp.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtavouqtvx.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtlifdyrjk.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtmkhydrpc.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtodwntooq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtvhyyvnin.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtuleuccze.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqnykennl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtggbkdmyr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtjxblkbtx.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtwmrvapre.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtopxukfip.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtanbhowzw.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtyogojidu.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtpdsvcpsg.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtfutdstxz.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtrgzoqydt.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtmmzqqare.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gtfhhnsjdb.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtbjqtxnhh.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtafvvxqsy.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtwqifplka.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gtpencxzfn.html


<!-- 参考信息 -->