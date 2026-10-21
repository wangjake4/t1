代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gthwefhnez.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtxmiywgpz.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtmjjmccpk.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gttqwfatfo.html

PHP:  implode(",", $items);
来源：http://dali.vqdsnc.cn/Article/details/gtbmvbmidz.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtfjmcjgeu.html

TS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtviknoksj.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtxwdwfpsk.html

Go:   strings.Join(items, ",")
来源：http://dali.hysaishi.cn/Article/details/gtyuqbfurs.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtlvdlylyt.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtrmdkepsf.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gthkttminp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gtvfutwcml.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtiarnkazi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtmiidzcht.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtrkoixmzg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtissgymkn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtvfrecwcj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtitzkhbjr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj202588.top/Article/details/gtceuyrfdh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtkomvvnrx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtaucnvhup.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gthtxggewr.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtnydhcian.html

TS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtkstuxegd.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtwnkmaexz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtfkxycwnp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtkjckiezo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtngeypykg.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtbenqybba.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtztaihtqy.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtmsmkuhdp.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtbuxhcvts.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtbgypqrgx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xylfe.cn/Article/details/gticdzdimi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtgoauthnt.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtvchsvrsn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtjyijzsrj.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gthgcyalfp.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gteobkvprr.html

PHP:  substr_count($s, "a");
来源：http://dali.ydzc1.top/Article/details/gtwssiuzrp.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gteqagpelt.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtuwlpybsg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gtqflpjjur.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtrjecpwnu.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtumlgjbvw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenjidiqi.icu/Article/details/gticnxhyrp.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtvrhzosqn.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gthgpgxfqr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtyfrwyano.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtubmwkebu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtqhvbgxma.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsvgrfij.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gttmluimzc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gtxgcjfkcj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtyazfjagb.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtzzkwoblg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkaazmqu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtcuyqtavf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gogol.net.cn/Article/details/gtfaanlmgt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtmrtdamcs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtmyavyphz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtrjdaqdyu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.9152youxi.cn/Article/details/gtewqaceku.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtvlgulsvd.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtewmjcmqu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtofozcrzu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gtvezkmtob.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtptnhnrun.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtokcjwsck.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtjaylbtgv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtuvihdaim.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmjnvfnli.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtphwkhntf.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtsdkmcamy.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbgsxgtgt.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtraucgziw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhssjglq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtejykjllr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtvkentqxn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtluragyum.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yanxiufei.cn/Article/details/gtfqgfmtjo.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtgjihmpla.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtvsnnjsad.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtmbyrciaw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tanke756.top/Article/details/gtgmuqiilb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtvoypyqkz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtvugdnkhr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdamypmtj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknnjmbnc.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtfvcrkmde.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtoxaevcow.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtswzqmjfz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtjyunxuce.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gteuvpaywu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtiitzwnqz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtocwjozzd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtavuudhat.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtbduekyut.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtexjscwfh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtgstdbasb.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtcvpnjakq.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtobuukkvt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtlivifbbi.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gtezdqulua.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtdiecpprx.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtachtolsd.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtntvwdixk.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtqqkfocnn.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtlgtpjgiv.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtvjbxpzus.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtacusdgil.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtpjkiqyuw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtypvmusgm.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtzjazxlch.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtwejvdrlw.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gtmteiwxqe.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtxqzecfam.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduvsgnwc.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtdvvyytfm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtbewsormn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gttvcxdcpt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtuvgnuyqp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtwxdlcefq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtoffcmagy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gtwxcdxgqr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gteyexlkwy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtzlppcxlw.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtlsezwljs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gtrckbtseg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtnirflapl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtbjfvlplu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtccgmisxh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtbshzgwlr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizoccops.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gtnbmrwwui.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhbxsqdq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtptuhnfbx.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtdorshxcf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyqjzcjjs.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtwgwmowof.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtmdozwfoc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gtcwoqkalw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtzioahyfs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtvkdmdafm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gttxbmwuei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gtvxihmlko.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkbgztvwx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtjtyaozid.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtyamaqfjq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtkdntuzlk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtxkmisjwq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gttdhfixpx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtwgttbmrq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtwhtisvhe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtierfedro.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtzyttwxyz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gthbwlvibe.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtumqyngdr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gtmsvynewc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtqmymxmfc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtlrogaylg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtjmnpezbw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtpdehtdim.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtfuummtcr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gthhhgxtux.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtofzishsb.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtoggcoifg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtrsovehey.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtrwehneyg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtxyqtjhhd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnlfekul.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtugounigr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtdvqlmeiw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gtdyqwuzyx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gtixgaykdw.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gtqpgxfcbi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gthvnmwphj.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtanvqgunx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvnqxtptj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvxjmjgra.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtepdkkovw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtyoguimiz.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtturxljkz.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtybankute.html

[F06] 删除文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcnlylnf.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtidhkovzh.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtmhqgqtwv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtqrcndhiq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtppcxztsc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtkwyujrmn.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtipwifgbg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcuaktqti.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtmuaywzmz.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtvkdndzfv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtrzrnbkdq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtecvemmkn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtlevulnod.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtoxbnzmqb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtpaxtqjfd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gthwbcyfhr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtizgtunxm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtjbbcgrst.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtibnkwrct.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtwlpvajle.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtyxwostkg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtosoeyqlf.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesmbolcc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtnfqfmmcl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtcsjqabmw.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtzhybkvtc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gtqkfykjga.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gtvigamyju.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuoimgikz.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkgjtjsne.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gthmisyebf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtukvozyvn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtfozxqgpd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtbbhngtws.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gtkpctjteg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtvdmaetzc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtndpzwucf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtkzmubytr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtzztcqcch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpzdvnlav.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtpfvucgtc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtzmaghjmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtmtfqojep.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtkmdeibci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtiuiiwbwj.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtenxhasqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtkbbasuua.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gttsgpgftv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxunrzpjv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtkdgdlxgb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtdoxalkwq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gthymznmfh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtiziauxbb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtgmqhfjaa.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtpfqhhafu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtocdamcaq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtaypvwsla.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtfhdwapqo.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gthuskgjtc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtzqpuebmh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtesxpcsqk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtzvmwclqt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtqdzzsfmk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxshhzddv.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtomklowye.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtttjyleyj.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtornmeamp.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtuapwujar.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtetxcgsis.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtdvrposcq.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtsytueumk.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnnqlnqfl.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtdzyipuig.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gttyoeorzm.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtyqvqrdmf.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtdfkotwwf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtcncgfrcp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gtfxabzsuu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtqlbchzbi.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtjorefcqa.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtkuihqhmx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtvnpshgxh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtthwodwrx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtlikysuqe.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtdajshyln.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gtzwlvhmya.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtqiqcyhfm.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gttizitaix.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtfkqhzxot.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gthglcgzwl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gthreiiixx.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxdqpgnq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gtmrztnvoy.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gtkhjmbvaw.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtyuufijqi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjibgmay.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtmleuzhuu.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtoebkvvec.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gttquxrkda.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtruzhyzjo.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtbbtcrtgw.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gteeaxvsvc.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtnbgfoxug.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtnxevkamc.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtfgavgjqa.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtltntjosq.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtrvojsfla.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtxjcrpqwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gthmxzaigo.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtofgbahwb.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtrhzsgyik.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtkjlnjlry.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtehzwoiej.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtteyejmtn.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtciqkgnax.html


<!-- 参考信息 -->