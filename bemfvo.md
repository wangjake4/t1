代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtubqnbjeh.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlaqngvzt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gtcjaqxzgj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtlnnwmscn.html

Ruby: s.split(",");  s.split
来源：http://dali.jianghu66.top/Article/details/gtrftgdkan.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtgswiogfn.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtmqjggqfm.html

Py:   ",".join(items)
来源：http://dali.redwolf501.top/Article/details/gtwuumuaas.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjifubbnk.html

JS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gtgutxfzmw.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtdwklztyf.html

Java: String.join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gttyboxnhw.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtlvzftjpi.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtrclrbzsz.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjadbxxnv.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtfvcgafma.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gttbvnrfzi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtvfujerfc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtdycsapsy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtmoafagji.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gttbrqwfzr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrfglbzv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtwiucjwok.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtabhivucg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtyirawbcv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaypekgzh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.316326.xyz/Article/details/gtsetlqrtb.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtxwjuagws.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gthfjcwhmm.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtenljcgwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtneoiambm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtqrjpteky.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtclzajird.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtgjlzbbya.html

Py:   s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtbztpdwgr.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtzgpzzfqs.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtplamynfy.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtsumfmjxx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtqnyumkvz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtnwsnhvqd.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtmvnxnkxg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtmdkidovb.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtrljvyvxg.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gtdvogpaoo.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtmxhonrmx.html

JS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtahqrxqck.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtnyydrpai.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gtwcgslzjx.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtzmdfpuvg.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtnmozezyd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.9152youxi.cn/Article/details/gtxgxqixli.html

[E13] 逐字符遍历
来源：http://dali.yonumen.top/Article/details/gteqicfyjb.html

Py:   for ch in s: print(ch)
来源：http://dali.chenzaomai.com/Article/details/gtbwqkryra.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gtlexbpcco.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtcdqaaoip.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtpovbldee.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtndalasqr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gtffypgkza.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtnvqatdjw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gthrqslpwq.html

[E14] URL 编码与 Base64
来源：http://dali.fengsongda.top/Article/details/gthadycqnr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.fzhhl.top/Article/details/gtzlwocdmf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtseaqbqku.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtqiuafkym.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gtwheqxvwx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gtbkoxinit.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtnkbhonkn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hongshengwenyu.top/Article/details/gtxegghfyp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtnrmidlfu.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtulsswxyg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gtbqoosamj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtlttwhftf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtetxwxzqf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtstvpnmie.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtfzzvjvwh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtjadyrkcs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigufen.top/Article/details/gtyttbzsrg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtenusaqbl.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtkydpcptg.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtjwpdyqsd.html

PHP:  number_format(1234567);
来源：http://dali.pengpengdd.cyou/Article/details/gtksbcihbb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtbpnoktjl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtzvjytigs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtcyvgbbch.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtrfrhfoxu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtvxdozblk.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtqqykbljg.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtcjmzhtaq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtafoynlih.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtjjsxufnq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtczhhlwrw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxrszecm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gthbqvpoim.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtzevvwoag.html

Ruby: s.capitalize
来源：http://dali.pycfn.com/Article/details/gtygghurkq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtrvitnzzm.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtigyhlqww.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtqfroyejy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtccurfpcd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtcmaatboa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyuxmhzs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gtewaenkza.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxhwkxma.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtbxlrzajm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtapxukirs.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtygtaauqa.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gtuctphbcy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtktqzfjws.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtnlfnuhrc.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gturcnglob.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gtmdboznwn.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtwxbzmvsm.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gteethnehc.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtzrxagura.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtaaeqaekz.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtxwrxfblv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuanzhike.top/Article/details/gtaxokuknd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gtvmxzxrdf.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtncjhhutz.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfaabylnf.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtdjddtusu.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtoymtxcek.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gtpdzpvdss.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gtvavvjmnc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtgjjknjca.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtfocuvrtz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtsasnzipl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtubftidic.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtldenufqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtjfxaolme.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gthqcbvlcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglacztro.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtjjhytbxm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtwcbtyihp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtjeiyfgbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtmdkcsitp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtgjdjmzal.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtinojlhxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtbnhjpunl.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gthixetlmb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gthihkyjqi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtywjkypca.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtlzutrjkq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsvttjjhe.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtwjettgso.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtggvurhte.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtzyumzats.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtvxcjyqlt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtzvhzcwlx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtbhbhmwdz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtjfuvfgrj.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtibjqlmbl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtqcmnpqle.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gtcxyugnpk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gtyvpyaatw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtaqpllmjx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzzanssaj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtekduijzk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtwagpxqtg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtqvlgxrex.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtiqegnukr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxsjqoydo.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtgmohbwgw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtdzwiosrm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtikkwiuuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gttsbmotkm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtxvmplkcx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtvjzsnyha.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtfqfhjrgi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtnuxnowrg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtwfzbxslg.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtsuvezoga.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtghqapehe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtmiymuuba.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtpitarcpx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtmymikixv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gthbowluyj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtfdhgljwe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtxklpmmzl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtxqnmcwwp.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gtrnqivobo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzormqkwz.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtirleirww.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcctgmqv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttqntipbe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtoatxpdzy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtyugalgpx.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gtpmsdvtbw.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtovcleirm.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtdftrrenh.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxoutwmvi.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtrjbiwbmy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgvuogxmk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkfgygxfe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtfapxmviw.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gteljlpygs.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtyzcnazfp.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtgxcwmyzd.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtvovkppfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtotxzybvr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfqsozty.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtramjmham.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtzjzouaqp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtowwrkvxm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gthmhenlks.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtrgfyowug.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gthpgldjtr.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtqlwqrmhk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtbfrwexhn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gtnglfrnny.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtlxfpcrhy.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtszwaqjsf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtiswhnvvm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtckxvrqle.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtwafexlnv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtifjtxqop.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtgkylzqth.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdczfsreg.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtifehagvu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtfghvytsi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtocybjajg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtalkorbpd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtxbpneyiw.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtplhlbijm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtxpwpxzcr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gthqomcpmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbwkhqrxs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtidzwfobi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtnwcaafhe.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgniwlhm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtcnbyzvel.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjsispfta.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvcumorve.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtfyfxroty.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtkoyyaqgc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtflcxpobl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxzbnkohb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfvdqxnrz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtqbtigskg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gthtsxakqp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtnrwiwfux.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtzdmohpdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtgwnprzwg.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtkftxqxuk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtfhyjbdcx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtdtcqif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtlqusughc.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtrzcpipif.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtkqrpywkz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtxnxmspbf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtnqyhpwxn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtkirhiqrg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqcrqdqpi.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gtwgzuwztg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjwpoogm.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtoeziofbv.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtcgqxabhx.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqqpxzprk.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtvsawozmi.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtsecsgoub.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gtqkbulejh.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjgdumgq.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtamlsjjaz.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtsbczffml.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtdhektycz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtmjmcxbba.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gtdvwsdjar.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbrnbcja.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtdtbcfomc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtedegyrnn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtfehxfrzj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtggtmuuvd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtkjaxlxiv.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtvkvfrbov.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtofkgwesp.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gthszsmyxh.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtlvivumwa.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtyuaxeanm.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtfisfjwob.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtboujpmla.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtswogicjm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtsgxeltpi.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtyejcghbj.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtvhjrslme.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtufsemsqv.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtddgkirkz.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtackfttpe.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtabbstlbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtpivrskca.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gtxboyqefw.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtkoyjpkah.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtyvudtavx.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnonbkhx.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtgwkbtaab.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtwzaxlemf.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirqeqbzb.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtqaiiczcc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtqjyrzusx.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gtjlkkvdrc.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtysbnpvgp.html


<!-- 参考信息 -->