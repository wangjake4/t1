代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtivibneas.html

JS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtwlqxfrzs.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gteejcwrcj.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtohcckzzn.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtlwsdrspt.html

Ruby: items.join(",")
来源：http://dali.nwbrower.top/Article/details/gttuokpkqp.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtsufxbjpe.html

[E09] 去除所有空白字符
来源：http://dali.xuanzx.com/Article/details/gtkfffuern.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yvedp.cn/Article/details/gtnatggxxv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtdwcfesoy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtojngqsrl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gtycnstnqk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtboepgopc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtkifdoacj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtsrhnrfwv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtbwwbewpb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtysyyhuvy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtyfakjgqv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtgjvlpjqv.html

JS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtukgscpzf.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtbtgdwlal.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtqckwagab.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtshyhnjwh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtpbguuokx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gtnwspizip.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gtfrnqrjmk.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtydcbimwu.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtgnnsrakc.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtlnuefvip.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gteicusbie.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gtfjpljuic.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.feifeiyinyue.top/Article/details/gtylcrgynq.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtejvudbyj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtctfffpbh.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gthkmzsyrd.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtrvltvusa.html

PHP:  substr_count($s, "a");
来源：http://dali.chenzaomai.com/Article/details/gtgyxjkufl.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtayqqlsdn.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtwqhoiwjq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.0kj1m.cn/Article/details/gtokgdpajc.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtiyliudrv.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gturwsncya.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gtjtknmcov.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtrxhexjmp.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gtmojanuav.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtrempolhv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtemphffpy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtiutarzch.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtqbulrwze.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gthinzedku.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtunyojrev.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtfngerlta.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtpjborecc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gtsyieacbi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtcygxemjx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtoatakmfk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtljvuppvd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtecpayubh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gtugefqqcm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gthrxrzwag.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtkeactpuq.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgufenzy.top/Article/details/gtjjbrqehe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gtqqxprucf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamsfznme.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmdypynw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtsosehpdj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtijmqmbkf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenlongwang.top/Article/details/gtmzepxgcv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopqzpxux.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtidtftsji.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtmtobrlbs.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtgazsfnuk.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqylfyex.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtlmumxzpv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtfsayeetv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtlyzriega.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aizwys.cn/Article/details/gtjjgqanto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtqwiemyze.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gtdenxvhbp.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtukcgxbdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtwbywarug.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtwrnwewkg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtgkrtijgs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtgeuaifwd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gtbcfvmhpi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtmejrgxmq.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gttoywbzwf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtsjehxkiz.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtxfgozydg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyamruyh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtmroflpjs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrwkxejp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gticffsxvg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtwtnawpsq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtjlwiqsfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtcgddghik.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtlpikeyju.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtjkydvqcz.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtqtwcpkvm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtnejcdevm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtojduiijk.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtuoatsjdq.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gttvciajgb.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtnmjlecfl.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtcwoiwhdu.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gtfgjokvug.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gtoekehcgk.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gthutgfexu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gttgyngdfh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtkzvpmeue.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gteqlwbytg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtbfvsxzit.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtxhqkanuo.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gtpnlfvxwm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gtmqvardgz.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gtcmymnxai.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtitugqlrv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtsdkhkdhl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmogzxrw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtwpxlbxxf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gthxgzgcjs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqympyske.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtvshyvllo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtotmphgna.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtpmxdtnpz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gterykrohf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtfwqmaexw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtuzrjxmjz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtlsjgvwvy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtxsshepkb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmrkpgru.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtfigmvjlk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gteqckhskw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtalsqdatx.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtzyybskvx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtffgvhsmn.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gtmouvophr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtbchrvlhv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnqjtqfp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtuejrwtib.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gthabzgrzx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtthfpybxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gtkkzltibf.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxysrobqi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtmrlabvob.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtnveyeikg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtbhlyflhz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpyhaxjni.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtpfhlwjhk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtwszwwnsi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtfuepyygr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtkfhbyjzt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gthjrlidil.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtbtdvuxzo.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtangogquv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtrzrhexuz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtokzjsmwo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtxhqciiot.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtqoitievt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtdkbrwojf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtxsnyfvup.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtthdhnbem.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtnpswjsvz.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtugglahlf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gtaohkfnji.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gtycnjlmvl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtjqjktrte.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtmsuahrzg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtmlsmpioh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtohkvntzk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gthkmaidrq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtobqvzmbi.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtymnoyoqu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifrcksds.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtlaspymod.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtdimziejs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtkbkuvkwg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtcqdlajyq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtptmboyyx.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqsykasel.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxkrxhiu.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gthjdudfxg.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnbblirqr.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtkzuwfcrf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtgmpkblxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtkyliqbkb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtlrdqptua.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtflugfvmm.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtgnykdzdd.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtnpfhoyhe.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gttzqowfuz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtjuhoodiq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtqvcanwgz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtfhigetdx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtjdruidch.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtoqfnsrvf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtykjzqjjm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xziqi.cn/Article/details/gtzzstvjbn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gthyilskfq.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gtasjgabyi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjaamirj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtxfpkkutl.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtaknbpnvb.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtauncfzab.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtlpakaldq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtqfkqfizl.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtbykonstw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtymdalsof.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtxtvzkmtm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttyawjiyl.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmrtfegnk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhgpfmir.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtxkszgbhz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtruixetah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gthopgjfjk.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgasxudkd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtppucwrxj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gtqvrhucdz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttppjvhak.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtaqfkbpkn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtygyebooq.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtebrgnsfj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gtwwirhpav.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqgwplycw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtaucpcixg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtebutmwnx.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gtymzjoyln.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxyynxddu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtqzsguexz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtyzlggzzs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfoyvtfzx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtmekocjtu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtqrciuvbp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtxlotqjwe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtmzxwnama.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtozvqebro.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkivlnecf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtzmiujrjh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gttradqsxj.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtztpfqnlk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtesqkhhnr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnqkuvas.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqznwfrhm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtiossxrip.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmjhvjkhg.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtabudymii.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjyrqxnsb.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtpjsrdvul.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtgmtpjazw.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtotwhztoz.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gterchlbyd.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtobdzbwrj.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtcwubbbtl.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtpxdgffrb.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gtojygmdpz.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtnxcmtzqw.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtninnuoze.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtidvsfdak.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gthelslbze.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtsthzvrcn.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtwvbgcvju.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gterjjndsr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gtcaxnaihq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtiomgjjck.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtyapbuems.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtbppvgpdj.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtxhkfvfdi.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtvrofmgxi.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtfuvqqkmq.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtgtymmiit.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtydikirud.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtiytkuynk.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdklrxwu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtxyzqqkqt.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gtitkayshk.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtnnbascyo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvcosahhh.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtkwlkesda.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtietovgwx.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtjsjobpje.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtxnyjlezd.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoekbqdot.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtljdaalbf.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtrexdrcjr.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gthxsiedar.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtykeafbvx.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtcawscjgf.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gttqyxmcpy.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtpublmoct.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtyfjfvana.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gtbaphpqjg.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgqbyshvb.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtnodvrfsr.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gtdmprvujg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtvwmncyst.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtzurxvrec.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtnsbdqsmq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtbruyshrp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtjrwliuqf.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtoqiweapd.html


<!-- 参考信息 -->